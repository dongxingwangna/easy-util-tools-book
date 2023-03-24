---
description: This class can be used to record time
---

# TimeMonitoring(时间统计)

```javascript
//Import the class
import { TimeMonitoring } from 'easy-util-tools'

//The instantiation class parameters are the element that counts the operation time, the event list of the operation, the delay of the automatic pause statistics, the callback that starts the timer, the callback that runs the timer, and the callback that the timer ends
let timeMonitoring = new TimeMonitoring(el, listeners: string[], autoPauseTime, startFun, running, end)

//Description of the parameter function：

// The function executes before the timing starts and has no type parameters
startFun()

// This method is executed during the timing process, and the parameters are the recording status, the timing time, and the total time
running(isRunning, currentSeconds, total) 

// This method is executed after the end of timing, and the parameters are running state, total time, and timing timeline
end(isRunning, total, timeLine) 

//Start the timer
timeMonitoring.run()

// Get time The input parameter is autoDestroy true or false indicates whether the default value of automatic destruction is false if true After returning the time, component events and timers will be destroyed, and the return value is the object containing total, timeLIne
timeMonitoring.getTime()

// To destroy instance event listeners, and timers, this method has no return value
timeMonitoring.destroy()

// This method is used to pause the timing, This method does not clear records that have already been timed
timeMonitoring.wait()

//  This method is used to continue timing
timeMonitoring.continue()

// This method is used to reset the timer, This method clears all records and re-records
timeMonitoring.reset()
```
