<!-- omit in toc -->
# Software & Network Rules

- [Network](#network)
- [RCS Black Box](#rcs-black-box)

## Network

  1. Teams are not allowed to use their own personal network devices to communicate with the go-kart from the pit.
  2. Each team will be provided an ethernet drop that will be able to connect to the go-kart on the track.
  3. Each team is expected to have a [Ubiquiti Bullet AC](https://store.ui.com/us/en/products/bulletac-ip67) for communication on the track.
     * [Non weatherproof version](https://store.ui.com/us/en/category/all-wireless/products/b-db-ac) - *use at your own risk*
     * *More information will be provided in how to setup the bullet network in the wiki.*



## RCS Black Box

  > The Race Control System Black Box is a standalone device (with its own internal battery) that will provided to teams at the competition for use of managing go-kart and track safety. All software and designs will be made public. The Black Box network will be completely managed by AKS officials, is 100% visible to teams, and will only handle information described below.

  1. Teams are expected to be able to interface with RCS Black Box via CANBus or USB.
  2. Teams are expected to send the following information **TO** the RCS Black Box
     * Motor Output Power to the Drivetrain
     * Health Status - *status options to be provided*
     * Control Mode - **Autonomous** or **RC**
     * Speed - **m/s**
     * Steering - *may not be required*
  3. Teams will be provided the following information **FROM** the RCS Black Box.
     * Track State - *states options to be provided*
     * Allowed Control Mode - **Autonomous** or **RC**
     * GPS RTCM
  4. Teams will be provided a software library to integrate into their existing autonomy stack.
     * The library will be available as a C++/Python library or as a ROS2 package.