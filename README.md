To Change to a new UID all you need to do is convert your number Decimal number to HEX.

You can use - https://www.rapidtables.com/convert/number/decimal-to-hex.html

In the Arduino program you will find a line below ->

/* Set your new UID here! */
byte newUid[] = {0xDE, 0xAD, 0xBE, 0xEF};

Change the converted HEX number with abbreviation 0xHEX 

For Example,

New UID in Decimal = 1234567890
New UID in HEX = 49 96 02 D2
New UID in HEX with 0x = 0x49, 0x96, 0x02, 0xD2 -> 

set this as your new ID upload it to the Arduino and present the card
