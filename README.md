# for-brainflayer
some tool for brainflayer (brainwallet cracking)<br>
https://github.com/ryancdotorg/brainflayer<br>


### bitcoin puzzle
pip3 install bit<br>
python3 puzzle.py \< bit \><br>
example for 66 bit puzzle :<br>
```
python3 puzzle.py 66
0000000000000000000000000000000000000000000000034f7030c8aaf422e7
0000000000000000000000000000000000000000000000035d554e690b893e41
0000000000000000000000000000000000000000000000029eb02aa6cc332be6
0000000000000000000000000000000000000000000000028da2e6c49a202655
...
python3 puzzle 66 | ./brainflayer -v -c c -b 66.blf -t priv -x -o output.txt
rate:   9038.34 p/s found:     0/24576      elapsed:    2.594 s
...
```
### mnemonics word
python3 mnemonics.py \< number of mnemonics word \><br>
example for 12 mnemonics word :<br>
```
python3 mnemonics.py 12
picture waste cruel riot lady lift venture path erode sauce narrow expose
angry final exotic raccoon stable sibling start shoe leopard salon bag knife
wool horn jar only curtain sail journey fog come dentist boss aunt
brisk card hazard theme patch badge text slab absurd donate predict where
...
python3 mnemonics.py 12 | ./brainflayer -v -b btc-addess.blf -o output.txt
rate:  23744.46 p/s found:     0/49152      elapsed:    2.097 s
...
```
### minikey
python3 minikey.py \< 22 | 30 \><br>
example for 22 minikey :<br>
```
python3 minikey.py 22
SXmQMA5szCKoPkhfu3i8G4
S4G8i3ufhkPoKCzs5AMQmX
SsuTCqJDwVX536dFRyUkSn
SnSkUyRFd635XVwDJqCTus
...
python3 minikey.py 22 | ./brainflayer -v -b minikey.blf -o output.txt
rate:  23744.46 p/s found:     0/49152      elapsed:    2.097 s
```
