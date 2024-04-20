# android-beep-at-timer-sequence
beep at predefined intervals - useful for yoga, breathing practice, exercise, repetition with different sets


android-beep-at-timer-sequence

application data: /usr/share/app_name/sequence.txt

<beep sequence intervals - in persistance storage>
data format: [* for active; - for inactive]:[name]:[version]:[date created]:[first interval]:[next interval [one or many]]:[last interval]

* active [first one accepted; rest ignored.]
- inactive
% repeat in infinite loop
version and date created can be empty value

default sequence file:

*:breathing exercise:0:0:1:4:2
-:1sec beep:0:0:1:%
-:breathing exercise:0:0:1
-:plank:1:2:3

1. main screen: start/stop/pause;repeat counter; history box; clear button; settings button; log to file [start time/date, repeat counter;] current active sequence
2. add/edit/manage sequence screen; set active
 --- add first beep; add next beep - 1 times; save
3. history screen/share
4. settings screen - button to add sequence; option to set/get active sequence; option to select beep type screen; enable log

   
