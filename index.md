## Welcome to Android Debug Toolkit

A major challenge I have experienced while developing applications has been the problem of 

* not being able to tell if we are caching correctly, whether
* our images are scaling properly, or rather at what scale is it even being displayed, 
* If we are making network requests, how many are actually going through and how many are not, 
* Checking the rate of drain our code is putting on the batteries. How can this be quantified.
* If we are using dependency injection, We have loose touch with the instances and the graph of objects that are maintained
* Being able to toggle strictMode on the fly. Before we start the application and perhaps during its running
* Ability to see strict mode violations as they are happening.
* Check frame rates, and how they are changing,
* View heirarchy
* Toggle rate of animation
* Being able to goto the App-Info page straight from the app to un-install or clear memory.
* Being able to know the image compression algo applied by the library at any given point in time. Switch it on the fly and see how memory usage changes.
* Being able to check the health of the network connection, Run a speed test, How is this done? How do we analyse such a thing?
* Apply Jake Wahrton's Rise and Shine hack. See if it still works in the age of kotlin-API28 and beyond.

All this built on Kotlin and on the latest version of the android-SDK. 
