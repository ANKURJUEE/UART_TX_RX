# UART_TX_RX


 
Transmit 8 bits data from Basys 3 using the switches to the computer terminal through USB-UART connector on Basys 3. When a binary logic is set on switches [sw7:sw0], this forms a binary value (data bits) of an ASCII character. The character will show in the terminal (I used Teraterm, an open source). Transmission is triggered when a button is pressed. There is a button to reset the data as well.





UART stands for Universal Asynchronous Receiver Transmitter. It's a hardware communication protocol that uses asynchronous serial communication. UART is a set of rules for exchanging serial data between two devices.
In UART communication, two UARTs communicate directly with each other. The transmitting UART converts parallel data from a controlling device into serial form. The receiving UART then converts the serial data back into parallel data for the receiving device.
UART uses two wires between the transmitter and receiver. One wire is used for transmission and the second wire is used for reception. The UART interface consists of two pins: the Rx and Tx pin. The Rx pin is used to receive data and the Tx pin is used to transmit data. When two devices are connected using a UART, the Rx pin of one device is connected to the Tx pin of the second device.
The two types of signals used to complete data transmission are Txd and Rxd. Txd signifies the transmission side and Rxd represents the receiver end.
