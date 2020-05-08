# CCTry4000

In this project,  I designed a very useful UI, and I finished it all by blueprint so it should be very simple for all of you to try.

There are two reasons that I made it:
	1. When I worked in my team project, there were so many keyboard events.
	2. Sometimes I didn't think current keys' positions are suitable for me.
So I tried to allow players customize the keyboard events by theirselves so that they could explore our game more comfortable.

The key point of this project is the struct I made. According to the data saved in the struct, we would started our blueprint by 3 steps:
	1. Remove old information contains in the axis/action mapping event.
	2. Reset the member of the struct.
	3. Reimports new data from the structure into the axis/action mapping event.

Also, I tried to prevent the players from setting the same key for different action/axis event. However, now the action and the axis event are seperated, which means people cannot use same key to control different action mapping event or axis mapping event. But they can use same key to control an action mapping event and an axis mapping event. 
I would try to figure out this small problems in the futrue.
