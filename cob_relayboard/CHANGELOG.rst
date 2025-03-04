^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cob_relayboard
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.7.13 (2022-07-29)
-------------------

0.7.12 (2022-03-15)
-------------------

0.7.11 (2022-01-12)
-------------------

0.7.10 (2021-12-23)
-------------------

0.7.9 (2021-11-26)
------------------

0.7.8 (2021-10-19)
------------------

0.7.7 (2021-08-02)
------------------

0.7.6 (2021-05-10)
------------------

0.7.5 (2021-04-06)
------------------
* Merge pull request `#418 <https://github.com/ipa320/cob_driver/issues/418>`_ from fmessmer/fix_catkin_lint
  fix catkin_lint
* fix catkin_lint
* Contributors: Felix Messmer, fmessmer

0.7.4 (2020-10-14)
------------------
* Merge pull request `#417 <https://github.com/ipa320/cob_driver/issues/417>`_ from fmessmer/test_noetic
  test noetic
* Bump CMake version to avoid CMP0048 warning
* Contributors: Felix Messmer, fmessmer

0.7.3 (2020-03-18)
------------------

0.7.2 (2020-03-18)
------------------
* Merge pull request `#409 <https://github.com/ipa320/cob_driver/issues/409>`_ from LoyVanBeek/feature/python3_compatibility
  [ci_updates] pylint + Python3 compatibility
* fix pylint errors
* Merge pull request `#408 <https://github.com/ipa320/cob_driver/issues/408>`_ from fmessmer/ci_updates
  [travis] ci updates
* catkin_lint fixes
* Contributors: Felix Messmer, fmessmer

0.7.1 (2019-11-07)
------------------

0.7.0 (2019-08-06)
------------------
* Merge pull request `#396 <https://github.com/ipa320/cob_driver/issues/396>`_ from HannesBachter/indigo_dev
  0.6.15
* Contributors: Felix Messmer

0.6.15 (2019-07-17)
-------------------

0.6.14 (2019-06-07)
-------------------

0.6.13 (2019-03-14)
-------------------

0.6.12 (2018-07-21)
-------------------

0.6.11 (2018-01-07)
-------------------
* Merge remote-tracking branch 'origin/indigo_release_candidate' into indigo_dev
* Merge pull request `#341 <https://github.com/ipa320/cob_driver/issues/341>`_ from ipa-fxm/APACHE_license
  use license apache 2.0
* use license apache 2.0
* Contributors: Felix Messmer, ipa-fxm, ipa-uhr-mk

0.6.10 (2017-07-24)
-------------------

0.6.9 (2017-07-18)
------------------
* manually fix changelog
* Contributors: ipa-fxm

0.6.8 (2016-10-10)
------------------

0.6.7 (2016-04-02)
------------------

0.6.6 (2016-04-01)
------------------
* use aggregated power state message
* tabs vs. spaces
* harmonize publisher queue sizes
* relaynode delete slashes topics
* Contributors: Felix Gruber, ipa-fmw, ipa-fxm

0.6.5 (2015-08-31)
------------------

0.6.4 (2015-08-25)
------------------
* explicit dependency to boost
* remove obsolete autogenerated mainpage.dox files
* remove trailing whitespaces
* add_dependencies EXPORTED_TARGETS
* migrate to package format 2
* sort dependencies
* critically review dependencies
* Contributors: ipa-fxm

0.6.3 (2015-06-17)
------------------

0.6.2 (2014-12-15)
------------------

0.6.1 (2014-09-17)
------------------
* Deleted CurrentMeasurement.msg
* Re-add relayboard_sim
* fix install tags
* Current Measurement
* Current measurement
* Removed emergency model and custom Relayboard
* Merge branch 'groovy_dev' of https://github.com/ipa320/cob_driver into groovy_dev
  Conflicts:
  cob_relayboard/ros/src/new_method.py
  cob_relayboard/ros/src/relayboard_sim.py
* Thrash
* Emergency stop modeling
  * First Working Version for the Care-o-Bot
* Contributors: Thiago de Freitas, ipa-cob4-2, ipa-nhg, thiagodefreitas, thiagodefreitas@gmail.com

0.6.0 (2014-09-09)
------------------

0.5.7 (2014-08-26)
------------------
* Merge pull request `#163 <https://github.com/ipa320/cob_driver/issues/163>`_ from ipa320/hydro_dev
  updates from hydro_dev
* 0.5.6
* update changelog
* move EmergencyStopState.msg to cob_msgs + PowerBoardState works again
* Added queue_size=1 paramter to Publisher initialisation.
* changes due to introduction of cob_msgs
* small changes to remove warnings
* Cleaned up cob_driver with reduced deps to compile on indigo
* fix tabs vs spaces
* Fix python indentation problems
* Contributors: Alexander Bubeck, Denis Štogl, Felix Messmer, Florian Weisshardt, Scott K Logan, ipa-fxm

0.5.6 (2014-08-26)
------------------
* Merge pull request `#163 <https://github.com/ipa320/cob_driver/issues/163>`_ from ipa320/hydro_dev
  updates from hydro_dev
* move EmergencyStopState.msg to cob_msgs + PowerBoardState works again
* Added queue_size=1 paramter to Publisher initialisation.
* changes due to introduction of cob_msgs
* small changes to remove warnings
* Cleaned up cob_driver with reduced deps to compile on indigo
* fix tabs vs spaces
* Fix python indentation problems
* Contributors: Alexander Bubeck, Denis Štogl, Felix Messmer, Florian Weisshardt, Scott K Logan, ipa-fxm

0.5.3 (2014-03-31)
------------------
* install tags
* Contributors: ipa-fxm

0.5.2 (2014-03-20)
------------------

0.5.1 (2014-03-20)
------------------
* some install tag updates
* cleaup merge hell
* Revert "added pr2_msgs to dependencies" as this change has been introduced in commit cc92fd0e590b607b29ea73bcdd
  This reverts commit 203b52f3d9d4b26ef0db8e415e1aa3e883fbb708.
* merge changes from frederikhegger, `#80 <https://github.com/ipa320/cob_driver/issues/80>`_
* added pr2_msgs to dependencies
* changes for hydro
* fix compile bug
* merge
* common/src/SerRelayBoard.cpp
* Missed CmdRelaisBoard.h file
* Added version 3 for relayboard
* fix compiling bug for ubuntu > precise
* Installation stuff
* use v not mV
* use V and not mV
* removed power state publisher
* cleaned up CMakeLists and added install directives
* further modifications for catkin, now everything is compiling and linking
* compiling but still some linker errors
* Second catkinization push
* First catkinization, still need to update some CMakeLists.txt
* More organization to the voltage commit
* Organizing the voltage filter commit
* Reverting new_method
* First robot changes
* IPA PC
* added line buffering
* record voltage update
* discharge analysis
* discharge analysis
* voltage test
* added topic to publish voltage
* remove test
* move relayboard_sim launch file to cob_bringup
* add TODOs
* emergency stop message: misused wireless field from power_board/state message as scanner stop filed
* add simulated relayboard again
* removed deprecated yaml and launch files
* emergency stop topic for simulation
* using private namespace
* merge
* changed relayboard topics and reversed em state to work with pr2_dashboard
* additional config files for cob3-bosch
* additional battery interface
* added PowerState and PowerBoardState messages to relayboard for dashboard usage, fix naming issue in the powercubechain follow trajectory interface
* added roslaunch tests
* added cob3-4 configs
* additional config files for cob3-bosch
* added rostest
* missing file
* relayboard_sim.launch for icob
* icob changes
* update cob3-3
* rearranging cob_camera_sensors launch files
* config for cob3-3
* config for cob3-3
* camera settings added for head
* moved ultiple message files out of cob_msgs to their own packages
* added camera tests
* configurable relayboard
* release update for cob3-1
* cob_relayboard: Added support for different protocol versions as yaml parameter (esspecially NUM_BYTE_SEND)
* merge
* added configs for desire
* changed NUM_CHAR_BYTE: TODO as parameter for cob3-2
* small changes on relayboard
* edited Relayboard: now publishes only on topic, when succesfully connected to relayboard; when connection to relayboard breaks, publish EM_STOP_ACTIVE messages
* removed dependency to generic can
* cleanup in cob_driver
* new rostest file for relayboard
* included new rostest file relayboard.test
* renamed as relayboard.test
* hztest for emergency_stop_state
* included rostest
* devs for cob3-2
* restructured base_controller
* Now also with ElmoRecorderReadout feature low CPU costs in base_drive_chain
* much ado about nothing
* Modified launch files of cob_base_drive_chain, cob_relayboard, cob_undercaariage_ctrl and cob_teleop_ucar and made them hierarchic
* removed hard coded entry of camera-axis limit switch in CanDriveHarmonica
* small launch file adaptions
* relayboard fixed
* Fixed relayboard-bug - at first go (by opening serial connection with O_NONBLOCK flag)
* update documentation and deleted tf broadcaster
* modification on cob3-2
* adapted launchfiles and added relative drive service
* Renamed and worked on cob_drive_identification, moved Elmo Recorder services to cob_srvs
* merged in master and manually solved conflicts in base_drive_chain.cpp
* cleanup in stacks
* added dependency
* Merge branch 'review' into cpc-pk
* Deployment of undercarriage controller debugged and finished: launch-script cob_ucar_joy starts up relayboard, base_drive_chain and controller; also remaps topics and services in correct namespaces. Debugging of controller itself is work in progress: simplified and removed old stuff - code compiles - controller runs but appaerently has some bugs -> may not yet be used
* Merge branch 'review-cpc'
* Merge branch 'review' into cpc-pk
* debugging undercarriage drivers (base_drive_chain + relayboard + ucar_ctrl) - work in progress
* cleanup in cob_driver
* Makefile for cob_relayboard
* after merging current review
* modifications to cob_relayboard
* Added EmergencyStop Message containing the current em signals as well as current state (e.g. confirmed after using the key-switch); accordingly adapted the relayboard-node to output the EMState together with EM signals; Last but not least: Fixed a typing error in the platform node
* renamed to cob_
* renamed packages to cob_ convention
* Moved StrUtil and TimeStamp from canopen_motor to cob_utilities; Adapted CMakelists and manifest of related packages
* Merged Relayboard into master branch
* simple_drive_test on COB3
* Header copyright infos adapted
* cob_relayboard: adapted launchfile for setting com port there. Platform.ini not anymore used there
* Removed unused features of relayboard from cob_relayboard. Cleaned interface and added readable error responses
* Debugged Relaysboard Node - checked differnt cyclerates - tested operation
* cob_relayboard node is publishing EmergencyStop States (EM-Stop & ScannerStop) correctly (tested)
* Simple Publisher fpr EmergencyStopStates including launch file
* node added *g*
* Very basic RelayBoard node added, which only has ability to publish EmergencyStopStates
* cob_relayboard: SerialIO library added, SerRelBoard library added, properly linked and compiled, ready for starting with ros node..
* Added new package cob_relayboard in stack cob_driver
* Contributors: Alexander Bubeck, Christian, Christian Connette, Florian Weißhardt, Richard Bormann, Thiago de Freitas, abubeck, cob, cpc, cpc-pk, fmw, ipa, ipa-cob3-7, ipa-cpc, ipa-fmw, ipa-mig, ipa-nhg, ipa-tys, ipa-uhr, mfueller, thiagodefreitas, uh
