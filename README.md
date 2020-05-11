# CC Presentation of CustomMapping

In this project,  I designed a very useful UI, and I finished it all by blueprint so it should be very simple for all of you to try. You can download my uproject and refer to my blueprint setup.

Reasons
--
There are two reasons that I made it:
* When I worked in my team project, there were so many keyboard events.
* Sometimes I didn't think current keys' positions are suitable for me.
So I tried to allow players customize the keyboard events by theirselves so that they could explore our game more comfortable.

Implementation description
--
The key point of this project is the struct I made. According to the data saved in the struct, we would started our blueprint by 3 steps:
* Remove old information contains in the axis/action mapping event.
* Reset the member of the struct.
* Reimports new data from the structure into the axis/action mapping event.

Also, I tried to prevent the players from setting the same key for different action/axis event. However, now the action and the axis event are seperated, which means people cannot use same key to control different action mapping event or axis mapping event. But they can use same key to control an action mapping event and an axis mapping event. 

Future work
--
* Fix the problems of using one key to control different action and axis mapping event.
* Find a good way to alert players that they set a same key to control differnt events.

