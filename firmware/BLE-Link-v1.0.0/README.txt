The UART is configured to be available as follows:

CTS	P0_2 (Pin 2 on BLE Link)
RTS	P0_3 (Pin 6 on BLE Link)
TX 	P0_4 (Pin 4 on BLE Link)
RX 	P0_5 (Pin 5 on BLE Link)

CTS must be connected to ground for proper
operation even if hardware flow control (CTS/RTS) 
is not being used.

Additional ouput pins are connected as follows: 

Connected LED 			P1_7
Link/Connected Output		P0_0 (Alt Pin 6)
Sleep Wake-up Input		P0_1 (Alt Pin 2)