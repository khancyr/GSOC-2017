On Github use the search function with `is:pr author:khancyr created:>=2017-06-01` 

This is the list of the PR I made during the GSOC time. Some other contributions by reviewing other PR were also made !

[ArduPilot main repo](https://github.com/ArduPilot/ardupilot):
==============================================================

 - Rover: add better scheduler perf counter
	 - https://github.com/ArduPilot/ardupilot/pull/6828
	 - Need Review

 - Rover: change k_throttleLeft/Right range from +/- 1000 to +/-100
	 - https://github.com/ArduPilot/ardupilot/pull/6807
	 - Need rework.

 - Rover fix brushed 2
	 - https://github.com/ArduPilot/ardupilot/pull/6806
	 - Partially merged

 - Rover fix failsafe
	 - https://github.com/ArduPilot/ardupilot/pull/6804
	 - Fix potential bug. Not Merged : replaced by https://github.com/ArduPilot/ardupilot/pull/6822

 - AC_WPNav: Fix potential divide by 0
	 - https://github.com/ArduPilot/ardupilot/pull/6800
	 - Bug fix. Need Review

 - Rover add proximity
	 - https://github.com/ArduPilot/ardupilot/pull/6776
	 - Need https://github.com/ArduPilot/ardupilot/pull/6720 and https://github.com/ArduPilot/ardupilot/pull/6775. In waiting state

 - Rover add fence support
	 - https://github.com/ArduPilot/ardupilot/pull/6775
	 - Need https://github.com/ArduPilot/ardupilot/pull/6720. In waiting state

 - Rover fix brushed for normal rover
	 - https://github.com/ArduPilot/ardupilot/pull/6744
	 - Partly merged

 - AP_HAL_SITL: implement brushed pwm type support
	 - https://github.com/ArduPilot/ardupilot/pull/6734
	 - Implement the brushed support in SITL. Need Review

 - Inertialnav removal
	 - https://github.com/ArduPilot/ardupilot/pull/6720
	 - Removal of a library specific to copter but with multiple dependencies. Need more review and test.

 - Inertialnav removal part1
	 - https://github.com/ArduPilot/ardupilot/pull/6718
	 - Part of a bigger PR. Not Merged as no usefull

 - Rover add proximity (3/3)
	 - https://github.com/ArduPilot/ardupilot/pull/6681
	 - Based on https://github.com/ArduPilot/ardupilot/pull/6659. Not Merged : replace by https://github.com/ArduPilot/ardupilot/pull/6776

 - Rover add fence support (2/3)
	 - https://github.com/ArduPilot/ardupilot/pull/6660
	 - Based on https://github.com/ArduPilot/ardupilot/pull/6659. Not Merged : replace by https://github.com/ArduPilot/ardupilot/pull/6775

 - Fence: move copter fence_check to AP_Arming (1/3)
	 - https://github.com/ArduPilot/ardupilot/pull/6659
	 - Move copter specific lib to be use by other vehicle. After discussion it was needed. Not Merged

 - AP_Baro: fix instance shadowing
	 - https://github.com/ArduPilot/ardupilot/pull/6654
	 - Little fix. Merged

 - AC_Fence: reset fences breach on disable
	 - https://github.com/ArduPilot/ardupilot/pull/6635
	 - Little fix. Merged

 - Copter: report polygon fence breach
	 - https://github.com/ArduPilot/ardupilot/pull/6634
	 - Little fix. Merged

 - AP_Proximity: correct missing use of PROXIMITY_MAX_DIRECTION
	 - https://github.com/ArduPilot/ardupilot/pull/6598
	 - Little fix. Merged

 - Copter: move proximity to common
	 - https://github.com/ArduPilot/ardupilot/pull/6591
	 - Move copter specific lib to be use by other vehicle. Merged

 - Rover: rename sonar to rangefinder (NFC)
	 - https://github.com/ArduPilot/ardupilot/pull/6590
	 - Renaming for coherency. Merged

 - Rover mode
	 - https://github.com/ArduPilot/ardupilot/pull/6575
	 - Mode library for rover. Not Merged : replaced by https://github.com/ArduPilot/ardupilot/pull/6628

 - Rover motortest
	 - https://github.com/ArduPilot/ardupilot/pull/6569
	 - Motortest implementation for rover. Not Merged : replaced by https://github.com/ArduPilot/ardupilot/pull/6604

 - Rover: reoder rc and servo init
	 - https://github.com/ArduPilot/ardupilot/pull/6566
	 - Cleanup after motor lib. Merged

 - Rover first motorlib  Rover WIP
	 - https://github.com/ArduPilot/ardupilot/pull/6516
	 - First try on motorlib for rover. Not merged : replace by https://github.com/ArduPilot/ardupilot/pull/6547

 - Rover implement condition yaw and do_set_speed support
	 - https://github.com/ArduPilot/ardupilot/pull/6515
	 - Need rework. Not merged

 - Autotest: remove SKID_STEER_OUT from default param
	 - https://github.com/ArduPilot/ardupilot/pull/6512
	 - Fix autotest param. Merged

 - Common: add pwm_type
	 - https://github.com/ArduPilot/ardupilot/pull/6484
	 - Need to be rework. Not Merged

 - Rover prepare motorlib
	 - https://github.com/ArduPilot/ardupilot/pull/6483
	 - Clean pre motor lib. Merged

 - Distance sensors: allow to have sensor type for mavlink rangefinder
	 - https://github.com/ArduPilot/ardupilot/pull/6482
	 - Better usage of Distance sensors message, specially with ROS. Merged

 - Rover corrections to slew rate and safety limits
	 - https://github.com/ArduPilot/ardupilot/pull/6472
	 - Closed as merged from another PR

 - HAL_PX4: cope with brushed motors in read_last_sent()
	 - https://github.com/ArduPilot/ardupilot/pull/647
	 - Little fix from previous work. Merged

 - SRV_Channel: cope with large time jumps in slew rate limiter 
	 - https://github.com/ArduPilot/ardupilot/pull/6470
	 - Little fix from previous work. Merged

 - RFC: Rover motor lib  Rover WIP
	 - https://github.com/ArduPilot/ardupilot/pull/6461
	 - First version of motor lib. Not merged after discussion. More cleanup and changes were needed. Better version merged later

 - Ap motor clean style and fix some variable
	 - https://github.com/ArduPilot/ardupilot/pull/6440
	 - Rework Copter motor library in more C++ style. Not finished. Changes requested  

 - Fix some travis warning  DataFlash Library
	 - https://github.com/ArduPilot/ardupilot/pull/6430
	 - Little clean up. Merged

 - init_ardupilot cleanup and improvements
	 - https://github.com/ArduPilot/ardupilot/pull/6426 
	 - Exploration of ardupilot init code for the different vehicle type. Unfinished and not merged as it implies enormous work for little gain

 - Autotest: refactoring
	 - https://github.com/ArduPilot/ardupilot/pull/6360
	 - Preliminary works for new autotest ; Need review.
  
[ArduPilot Wiki](https://github.com/ArduPilot/ardupilot_wiki) :
===============================================================

 - Add distance sensors usage example and small fixes
	 - https://github.com/ArduPilot/ardupilot_wiki/pull/868
	 - Merged

 - More warning fix
	 - https://github.com/ArduPilot/ardupilot_wiki/pull/840
	 - Merged

 - Fix numerous warning in dev directory
	 - https://github.com/ArduPilot/ardupilot_wiki/pull/832
	 - Merged

 - ROS: add more documentation and initial tutorial
	 - https://github.com/ArduPilot/ardupilot_wiki/pull/830
	 - Merged

[Pymavlink](https://github.com/ArduPilot/pymavlink) :
=====================================================

 - mavutil: handle ONBOARD_CONTROLLER heartbeat as GCS one's
	 - https://github.com/ArduPilot/pymavlink/pull/87
	 - Merged
  
[Mavlink](https://github.com/ArduPilot/mavlink) :
=================================================

 - add: MAV_DISTANCE_SENSOR_RADAR & MAV_DISTANCE_SENSOR_UNKNOWN 
	 - https://github.com/ArduPilot/mavlink/pull/46
	 - Merged

[Mavros](https://github.com/mavlink/mavros) :
=============================================

 - Extras: add ardupilot rangefinder plugin
	 - https://github.com/mavlink/mavros/pull/746
	 - Merged
  
 - Distance sensors: uncrustify and and new sensor type
	 - https://github.com/mavlink/mavros/pull/747
	 - Merged

 - Extras: distance sensor don't spam when message are bounce back from FCU
	 - https://github.com/mavlink/mavros/pull/748
	 - Merged

 - apm_config.yaml: change prevent collision in distance_sensor id
	 - https://github.com/mavlink/mavros/pull/749
	 - Merged

[QGroundControl](https://github.com/mavlink/qgroundcontrol) :
=============================================================

 - Joystick: add a button to support negative thrust
	 - https://github.com/mavlink/qgroundcontrol/pull/5185
	 - Need Review

 - Add support for guided mode on ArduRover and safety page
	 - https://github.com/mavlink/qgroundcontrol/pull/5597
	 - Need Review
