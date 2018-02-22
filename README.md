# Python 3.6 FX Trader Boiler Plate code

This is a simple multi-threaded Python 3.6 program which connects to a number of AMQP (RabbitMQ) queues to exchange data with a remote trading venue. 

This code was developed to work with Dukascopy's Jforex which is a JAVA based trading platform provided by Dukascopy bank that can be extended with custom code. They offer free demo accounts which enables the use of the Jforex platform via a downloadable JNPL applet...

In this case custom JAVA code was developed to send OHLC and Position data from Jforex to message queues and also allow Jforex to receive 'trading commands' from this python program via a message queue.

Therefore in order for this code to be useful for you, you will need a trading platform that can send and receive data via a message queue...

This program was designed to be simple to use and tailor. 

The runner.py file runs the program by starting a number of functions in their own threads, these then call other functions using additional threads as needed and these additonal threads die off once complete.

It is a relatively simple program but works as needed and is stable, hopefully it may be useful as a starting point or for ideas in you own program...

------------------------------------------------------
Mark Smith December 2016 (Uploaded to GitHub Feb 2018)





