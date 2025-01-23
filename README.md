# IMGD5010 Assignment 1: Build Your Own Binary (BYOB)
In this assignment, I developed a binary code to create a daily schedule including the time of an event, what the event is, and what color to associate the event with.
# Create your own schedule
I enjoy organizing and colorcoding my daily life, so here is a fun challenge to do so using binary code. There are three main steps:
## Step 1: Choose the time
Each 4-bit word represents a time of day:

|Time|Binary Code|Time|Binary Code|
|---|---|---|---|
|6am|0000|2pm|1000|
|7am|0001|3pm|1001|
|8am|0010|4pm|1010|
|9am|0011|5pm|1011|
|10am|0100|6pm|1100|
|11am|0101|7pm|1101|
|12pm|0110|8pm|1110|
|1pm|0111|9pm|1111|

## Step 2: Choose the activity
Each 4-bit word represents a specific activity that you will be doing at that time:

|Activity|Binary Code|Activity|Binary Code|
|---|---|---|---|
|wake up|0000|class|1000|
|go to sleep|0001|homework|1001|
|nap|0010|exercise|1010|
|breakfast|0011|socialize|1011|
|lunch|0100|relaxing time|1100|
|dinner|0101|read|1101|
|snack|0110|chores|1110|
|doctor's appointment|0111|stretching|1111|

## Step 3: Choose the color
Choose a color to associate with the activity. Each 4-bit word represents a color:

|Color|Binary Code|Color|Binary Code|
|---|---|---|---|
|$\color{red}{\textsf{red}}$|0000|$\color{teal}{\textsf{teal}}$|1000|
|$\color{orange}{\textsf{orange}}$|0001|$\color{lime}{\textsf{lime}}$|1001|
|$\color{yellow}{\textsf{yellow}}$|0010|$\color{violet}{\textsf{violet}}$|1010|
|$\color{green}{\textsf{green}}$|0011|$\color{grey}{\textsf{grey}}$|1011|
|$\color{blue}{\textsf{blue}}$|0100|$\color{lightblue}{\textsf{light blue}}$|1100|
|$\color{purple}{\textsf{purple}}$|0101|$\color{magenta}{\textsf{magenta}}$|1101|
|$\color{pink}{\textsf{pink}}$|0110|$\color{olive}{\textsf{olive}}$|1110|
|$\color{aqua}{\textsf{aqua}}$|0111|$\color{brown}{\textsf{brown}}$|1111|

## Put it all together
Below is an example of how to put all of these steps together into a final schedule. As you can see, the example schedule that I made depicts a day in which I woke up at 7am, ate dinner at 7pm, and went to sleep at 9pm. I colorcoded both wake up and go to sleep as purple to associate those two together, as they both involve sleeping.

|Sample Schedule|
|---|
|7am  $\color{purple}{\textsf{wake up}}$|
|7pm  $\color{aqua}{\textsf{dinner}}$|
|9pm  $\color{purple}{\textsf{go to sleep}}$|

And here is the binary code associated with that schedule:

0001 0000 0101\
1101 0101 0111\
1111 0001 0101

## Challenge
Try to create your schedule for today and color code it!

## Tips
You can add multiple events to one time on your schedule.




