^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package gcloud_speech_utils
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.5 (2018-04-18)
------------------

0.0.4 (2017-10-07)
------------------
* Fixes a problem that the binrary/libraries are not packed into deb file (`#18 <https://github.com/CogRob/gcloud_speech/issues/18>`_)
* Contributors: Shengye Wang

0.0.3 (2017-10-06)
------------------
* Adds catkin_INCLUDE_DIRS to include_directories (`#16 <https://github.com/CogRob/gcloud_speech/issues/16>`_)
* Removes documentation about the project name command line flag (`#15 <https://github.com/CogRob/gcloud_speech/issues/15>`_)
  * Removes documentation about the project name command line flag
  * Removes extra comments in launch file
* Contributors: Shengye Wang

0.0.2 (2017-10-06)
------------------

0.0.1 (2017-10-06)
------------------
* Fixes missing Copyright text in README (`#12 <https://github.com/CogRob/gcloud_speech/issues/12>`_)
  * Fixes missing Copyright text in README
  * Use Logitech instead of Samson in example launch file
* Kills the microphone node when it fails to publish samples (`#10 <https://github.com/CogRob/gcloud_speech/issues/10>`_)
  * Kills the microphone node when it fails to publish samples
  * Makes the fatal timeout a flag
  * Add respawn to launch file to allow microphone plug in/plug out
* Removes the clicking sound in playback microphone node (`#9 <https://github.com/CogRob/gcloud_speech/issues/9>`_)
* gcloud_speech_utils was missing python-pyaudio dependency (`#8 <https://github.com/CogRob/gcloud_speech/issues/8>`_)
  * gcloud_speech_utils missing python-pyaudio dependency
  * Remove unused Queue import
* Adds a playback node to gcloud_speech_utils (`#7 <https://github.com/CogRob/gcloud_speech/issues/7>`_)
  * Adds a microphone playback node
  * Use a newer version of record_audio.cc, and adds a playback node to utils
* Adds documents and examples, fixes bugs. (`#6 <https://github.com/CogRob/gcloud_speech/issues/6>`_)
  * Move print_rms exclusively to utils package
  * Implements auto retrying if failed prematurely within 300ms (default)
  * Adds some information in README file
  * Documentation
  * Document update
  * URL better to be link
  * Adds a All-In-One launch file that demos the program
* Adds channel connect and channel check to google_speech (`#3 <https://github.com/CogRob/gcloud_speech/issues/3>`_)
* Initial commit. (`#1 <https://github.com/CogRob/gcloud_speech/issues/1>`_)
* Contributors: Shengye Wang
