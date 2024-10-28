## IMU Based Crash Detector
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Post-blue?style=flat&logo=linkedin)](https://www.linkedin.com/feed/update/urn:li:activity:7179530035710554113/)

**Description:**

As my final project for [Embedded in Embedded](https://embeddedinembedded.com/), a program run by [Garmin](https://www.garmin.com/en-CA/) to introduce students to Embedded Technologies, I created a rudimentary Inertial Measurement Unit (IMU) based collision detector using an [lsm6dsl](https://www.st.com/en/mems-and-sensors/lsm6dsl.html). It works by analyzing rapid changes in acceleration in the X and Y axes, as well rotational movement about the Z axis, something my simulated collisions seemed to consistently exhibit. Although a rudimentary way detecting a crash, it did yield relatively accurate results.

My original goal was to transmit crash data wirelessly using the ANT radio protocol, however time and logistics proved to make this very difficult to implement. I opted for a simple LCD screen and buzzer notification to notify when a collision had occurred.
![Project Image 1](https://media.licdn.com/dms/image/v2/D562DAQH1AgWKiFrWYQ/profile-treasury-image-shrink_1280_1280/profile-treasury-image-shrink_1280_1280/0/1711746828372?e=1729184400&v=beta&t=G5grtpdRYd8D_q4zTvyfdgLjZ_nvnoYZGu0NgYOxJ0U)
![Project Image 2](https://media.licdn.com/dms/image/v2/D562DAQFbCNFNn3N2sg/profile-treasury-image-shrink_800_800/profile-treasury-image-shrink_800_800/0/1711746756152?e=1729184400&v=beta&t=PXEyjNvS2ZaBeh0d6BgdZSYHZPyqhoMxuLfowG8-V9U)

