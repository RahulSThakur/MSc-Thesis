# MSc-Thesis
The University of Edinburgh


Power is one of the major concerns for designers and there are continuous efforts being made to reduce 
power consumption. Due to the absence of clock in the event driven system, power consumption can be 
reduced. These techniques can be used for wearable, implantable or digestible biomedical devices that 
are powered by a tiny battery that cannot be replaced or charged often. 
This project describes an event-driven data acquisition along with digital signal processing that can 
potentially offer significant energy and bandwidth savings.  
The methodology described in this report does not require a clock for sampling time, it is implemented 
using level-crossing sampling in amplitude of the analogue signal which generates non-uniform sampling 
points. The asynchronous method used here generates non-uniform samples, thus eliminating the use of 
the clock. An FIR filter is designed through an asynchronous processor. A delay that is required for the 
functioning of the FIR filter is designed and implemented using analogue components. 

![Thesis](https://user-images.githubusercontent.com/42945540/59370112-77a19b00-8d5f-11e9-8572-eb2a03241772.jpg)
