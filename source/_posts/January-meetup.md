layout: post
title: January meetup
date: 2015-01-15 14:29:00
tags: meetup
---
For [the first meetup of the year](,http://www.meetup.com/Munchen-Arduino-Meetup/events/219666917/)  we were lucky to have a number of [TI connected Launchpad boards](https://www.youtube.com/watch?v=n13odoXQYeo) including some sensor boards ("Boosterpacks"). TI sponsored those to [MunichMakeS](http://munichmakes.de).

The goal of the TivaC platform is to enable IoT applications. The MPUs are mostly ARM based. The best [TM4C123x based boards](http://www.ti.com/lsds/ti/microcontrollers_16-bit_32-bit/c2000_performance/control_automation/tm4c12x/overview.page) had an impressive clock speed of 120 MHz.

# First contact

Some of the meetup members liked the sensor boards, even more than the network capabilites of the boards.  For example, there was a booster pack with Motion sensors which many tried out at first, and via serial communication, it was quickly possible to read out data from body motion.

But we had a bit of problems too, the Wifi of the Makerspace was a bit shakey to maintain WLAN connection of many devices. So, the stopped at a bit the exploration into the IoT direction.

Also, at least 50% of the meetup members are used to working with MacOS and/or Linux. While Energia supports those, some had problems with the Java version of Energia. For example, Marten had to downgrade his installed Java version.

# Board pinouts

We had a bit trouble decyphering the pinouts of the boards. On one hand, this could be due to he many functions on the board. There are several push buttons mapped to pins, but not every input worked as expected compared to Arduino code. I found the header file: pins_energia.h very helpful to decode those. Also, the TMC4123x provides pull-up/pull-down input configurations, which are helpful, but it must be known where to look.

<img src="/images/pinout_tivac.png" />


# Conclusions

All in all, a very interesting hacking adventure. This meetup was certainly a bit more for advanced users. Some members borrowed a board for playing at home, and we are expecting to see more TivaC details soon.


Please help us making the [Arduino & Co meetup better by answering again some questions in a survey](https://de.surveymonkey.com/r/MTZFLC8).

<img src="/images/jan_meetup.jpg" />


