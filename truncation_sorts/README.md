#Hashing
In order to get below nlogn work in a sorting algorithm, one has to gain information from some other operation than comparing two numbers.
Many current sub nlogn sorting algorithms do this via the operation of hashing or more precisely interpreting information which was given 
as order data as location data. Hashing also refers to compressing data in a randomized manner.
#truncation
In this section we will define two sorts which use the operation of truncation.
This is a simple operation with reasonable interpretation of O(1) where we take an n bit number and round it down to a m bit number where n >= m.
Why would this help? on its own, I don't know. Combined with Hashing, it allows us to more quickly search for where a number belongs in an array.
