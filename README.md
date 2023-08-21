# for-brainflayer
some tool for brainflayer (brainwallet cracking)<br>
https://github.com/ryancdotorg/brainflayer<br>


### bitcoin puzzle
pip3 install bit<br>
python3 puzzle.py \<bit\><br>
example for 66 bit puzzle:<br>
```
python3 puzzle.py 66
0000000000000000000000000000000000000000000000034f7030c8aaf422e7
0000000000000000000000000000000000000000000000035d554e690b893e41
0000000000000000000000000000000000000000000000029eb02aa6cc332be6
0000000000000000000000000000000000000000000000028da2e6c49a202655
...
python3 puzzle 66 | ./brainflayer -v -c c -b 66.blf -t priv -x -o output.txt
Rate:   9038.34 p/s found:     0/24576      elapsed:    2.594 s
```
