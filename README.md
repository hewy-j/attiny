# attiny
Programming Attiny stuff with arduino

1. Upload jtag2updi to arduino.
2. Add 10+uF cap across reset and gnd of arduino
3. Connect pin 6 of arduino to UPDI pin of attiny with 4.7kR
4. Supply power and ground to attiny
5. Install Board Package from board manager. Board manager URL is:
    http://drazzy.com/package_drazzy.com_index.json
    File -> Preferences, enter the above URL in "Additional Boards Manager URLs"
    Tools -> Boards -> Boards Manager...
    Select "megaTinyCore by Spence Konde" and click "Install".

6. tools>select board & tools>programmer (jtag2updi)
7. Upload code to tiny

