#SimpleBus
SimpleBus is a messaging library for Python 3. It has been designed to be simple and easy to use.
SimpleBus is still under heavy development so next changes might break compatibility.

##Features
- Auto recovery in case of connection fall.
- Multiple transports. (only amqp implemented so far)
- Messages that fail all retires are send to an error queue (dead letter queue).
- Retry logic for all messages received, it support delay between retries.
- ... more coming

##Documentation
Soon...

##Installation
You can install SimpleBus via Python Package Index (PyPI).  
`$ pip install simplebus`

To use AMQP transport you need to install the [amqp-storm](https://github.com/eandersson/amqp-storm) library.  
`$ pip install amqp-storm`

##Feedback
Please use the [Issues](https://github.com/viniciuschiele/simplebus/issues) for feature requests and troubleshooting usage.