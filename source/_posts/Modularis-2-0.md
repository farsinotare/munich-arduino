title: Plug and Play Feedback Systems
date: 2015-05-31 14:38:33
tags: meetup
---
In the last meetup, [Dr. Matthias Bachmayer](https://twitter.com/Modularis2p0) presented his [Modularis platform](http://www.aevum-mechatronik.de/modularis/). Modularis is all about making [control theory](http://en.wikipedia.org/wiki/Control_theory) and [feedback](http://en.wikipedia.org/wiki/Feedback) work. Especially, if you want to build robots or [mechatronic devices](http://en.wikipedia.org/wiki/Mechatronics), control theory will play an important role.

According to Wikipedia, control theory "deals with the behavior of dynamical systems with inputs, and how their behavior is modified by feedback." To simplify the development of these systems, Mathias investigated a number of patterns and electronic building blocks. This is the background of the Modularis project, which has its roots in Matthias' dissertation research going back to 2005 (way back before Arduino became popular.)

<a href="https://www.flickr.com/photos/pmulder99/18304094405" title="Application overview of Modularis on Flickr"><img src="https://c2.staticflickr.com/8/7789/18304094405_41e687b85e_n.jpg" width="320" height="240" alt="uses"></a>

Modularis provides a number of sensors and actuators that can be easily connected with I2C and small connectors as shown below. While earlier Modularis boards had rather large connectors, the newer boards became tinier and friendler for advanced integrations. 

<a href="https://www.flickr.com/photos/pmulder99/18116274398" title="Modularis overview on Flickr"><img src="https://c1.staticflickr.com/9/8770/18116274398_99c8559f32_z.jpg" width="480" height="640" alt="Untitled"></a>

An important feature of Modularis is the use of the I2C bus. You can easily connect sensors and actuators with ribbon cable. And, you can connect a microcontroller for system control too. Currently, Modularis supports Atmega168 and Atmega328 microcontrollers which are easy to program with the common AVR tools. Matthias is experimenting with other microcontrollers such as ARM Cortex based devices too. But contact Matthias for more information on this.

We then had an overview of common Modularis boards, such as bridges for CAN and LIN, as well as Wifi. The Modularis system also works with a Raspberry Pi. The highlight of the evening was a demo of plotter that was built with Modularis.

<iframe width="420" height="315" src="https://www.youtube.com/embed/xt1jIpqrhD4" frameborder="0" allowfullscreen></iframe>

After the talk, we had some discussions about differences between Modularis and Arduino. Matthias explained that while Arduino is nice for basic electronics, he thinks that Modularis provides a much better entry point for learning about control theory and systems. We are planning to have some more meetups about teaching system design with Modularis soon. 
