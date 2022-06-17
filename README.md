# Stopwatch
Simple implementation of stopwatch functionality in C++, meant to mimic the Stopwatch from C#/.NET

The class is implemented entirely in the header file.

---
### Methods
|  Method| Description |
|--|--|
|IsRunning | Queries whether the stopwatch is currently running (.Start was called). |
| Start | Initiates an interval of the stopwatch |
| Stop | Stops the stopwatch, creating a closed interval from the start point.  |
| Elapsed | Returns time in seconds of currently running interval (After starting the stopwatch, without stopping it.)  |
| LastElapsed | Returns time in seconds of previous completed interval. |
| GetIntervalElapsed | Returns the elapsed time (in seconds) of the specified interval (index of intervals starts at 0). | 
| TotalElapsed | Returns time in seconds of all intervals + the currently running interval if stopwatch is running. |
| Reset | Erases all intervals. |
