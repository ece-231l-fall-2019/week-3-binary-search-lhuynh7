# Review of the code

When creating this code, I ran into many issues on how I would be able to get the results and timing of the program. After writing down what I should be expecting made visualizing the code a bit easier.  

## Linear vs Binary 

The difference between these two-searching algorithms is that Linear search checks every number checks each element until it finds the matching element. Binary search on the other hand finds the position of the value within a sorted array. These two-searching methods are very useful depending on the application.   

When it comes to the time difference for this application below, we can see that Binary is much more efficient because of how fast it found the value compared to Linear. Even with Optimizations the results for Binary beats Linear by a huge margin.


### Without Optimizations


| Algorithm           |Time         |
|--------------------|-------------|
|Linear              |18.4272s     | 
|Linear (pointers)   |15.1374s     |    
|Binary              |0.000949238s |
|Binary (pointers)   |0.000856337s |


### With Optimizations


|Algorithm           |Time         |
|--------------------|-------------|
|Linear              |14.1367s     |
|Linear (pointers)   |13.6677s     |
|Binary              |0.000960344s |
|Binary (pointers)   |0.000964609s |



# Summary

Although I was able to get some good results with and without Optimizations, it seem slower compared to the example that the professor had showed in class. I concluded that my speed and timing results were affected due to my hardware capability.
