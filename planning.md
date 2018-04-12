Inspiration
- http://g07cha.github.io/pomodoro/
- https://github.com/nikolavp/awesome-pomodoro
- https://github.com/ugol/pomodoro
- https://github.com/mehdidc/pomodoro
- https://github.com/lukaszbanasiak/YAPA
- 
Algorithm
- First 
    - Short Break
- Second
    - Short Break
- Third
    - Short Break
1. After four pomodoros, take a longer break (15–30 minutes), reset your checkmark count to zero, then go to step 1.
- Fourth
    - Long Break

Pseudocode
int cycles = 0
var defaultWorkTime in minutes = 25
//var variableWorkTime = defaultWorkTime

var defaultShortBreakTime in minutes = 5 minutes
//var variableShortBreakTime in minutes = defaultShortBreakTime

//longBreak must always be longer than short break

var defaultLongBreakTime in minutes = 30 minutes
//var variableLongBreakTime in minutes = defaultLongBreakTime

Start a session
while true/notPaused:
cycles ++;
begin work
	when work is finished
//(may pause and then ask user to begin instead of automatically doing so)
if (cycles != 4) {
	begin short break
} else {
	cycles = 0
	begin long break 
}
restart process (while should handle that)
