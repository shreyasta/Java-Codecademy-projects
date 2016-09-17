# Java-Codecademy-projects
Steps to create your own Droid

Create a public class called Droid.
2.
Create an int instance variable called batteryLevel. Do not set it equal to anything at the moment.
3.
Create a Droid constructor. Inside of the Droid constructor, set batteryLevel equal to 100. Now every time a Droid is created, its battery level will be at 100 percent.
4.
Next, create a method called activate. The method should not return any data type.
5.
Inside of activate, print out a message to the user that lets them know their Droid is activated and alive. For example: Activated. How can I help you?.
6.
All Droid actions should use up some battery life. On the next line, decrease the battery level by 5 percent.

Hint: batteryLevel is equal to batteryLevel minus 5.
7.
We should always update the user on the battery level every time the Droid performs an action. On the next line, print out the battery level.

Hint: System.out.println("Battery level is: " + batteryLevel + " percent.");.
8.
Let's provide a way for users to charge their Droid. Create a method called chargeBattery. It should accept an int parameter called hours. The method should not return any data type.
9.
The first thing the method should do is inform the user that their droid is charging. Print out Droid charging....
10.
Next, the battery level should increase by the number of hours specified by the user.

Hint: batteryLevel is equal to batteryLevel plus hours.
11.
We have to make sure the user doesn't overcharge the Droid. Inside of chargeBattery, write an if statement that checks if the battery level is greater than 100.
12.
If the battery level is greater than 100, set the battery level equal to 100, then print out the battery level to the user on the next line (refer to step 7 if you need help).
13.
Otherwise, in an else block, simply print out the value of the battery level to the user (refer to step 7 if you need help).
14.
Next, create a method called checkBatteryLevel. It should return an int.
15.
Inside of the method, print out the battery level to the user.
16.
On the next line, return the battery level.
17.
Create another method called hover. The method should not return a value. It should accept an int parameter called feet.
18.
This method will instruct the Droid to hover above the ground, but we can't let the Droid hover too far off the ground. Inside of the method, use an if statement to check if feet is greater than 2.
19.
Inside of the if statement, print out a friendly error to the user, for example: Error! I cannot hover above 2 feet.
20.
Otherwise, in an else block, print out to the user Hovering.... On the next line, decrease the battery level by 20.
21.
On the next line, print out the battery level to the user.
22.
Now create the main method.
23.
Inside of the main method, create a Droid object.
24.
On the next line, call the activate method on the object.
25.
Next, call the chargeBattery method and specify 5 as the hours parameter.
26.
Finally, call the hover method and specify a feet parameter.
27.
If you completed the project correctly, the output will indicate first a battery level of 95, then 100, then 80.
