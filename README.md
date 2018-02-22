# Python 3.6 FX Trader Boiler Plate code

This is a simple multi-threaded Python 3.6 program which connects to a number of AMQP (RabbitMQ) queues to send to and receive data from a trading venue. 

This code was developed to work with Dukascopy's Jforex which is a JAVA based trading platform that can be extended with custom code. 

In this case custom JAVA code was developed to send OHLC and Position data to message queues from Jforex and also allow Jforex to receive 'trading commands' from a message queue.

Therefore in order for this code to be useful for you, you will need a trading platform that can send and receive trading data from message queues...

------------------------------------------------------
Mark Smith December 2016 (Uploaded to GitHub Feb 2018)





