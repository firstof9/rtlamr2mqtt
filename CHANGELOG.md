### 2022-02-11
 - New configuration parameter: `state_class` (thanks to @JeffreyFalgout)
 - Automatic MQTT configuration when using the Addon (thanks to @JeffreyFalgout)
 - Fixed 255 characters limit for state value #86

### 2022-01-11
 - Happy new year! :)
 - Added "tickle_rtl_tcp" parameter to enable/disable the feature (explained below)
 - Added date/time to the log output
 - Added device_class configuration option #66 (thanks to @phidauex)
 - Some clean up in the README file!
 - Machine Learning to detect leaks still experimental and needs a lot of love to work properly

### 2021-12-01
 - Lots of changes!
 - Changed Docker container to use Debian Bullseye instead of Alpine
 - Added TinyDB to store past readings
 - Added Linear Regression to flag anomaly usage
 - Problems with the official python docker base image :(

### 2021-10-27
 - Many fixes regarding error handling
 - More comments inside the code
 - Some code cleanup
 - Fix a bug for MQTT anonymous message publishing discovered by @jeffeb3
 - Using latest code for both rtl-sdr and rtamr in the Dockerfile

### 2021-10-12
 - The HA-ADDON is working now! A shout-out to @AnthonyPluth for his hard work!!! \o/
 - New feature to allow this container to run with a remote rtl_tcp. Thanks to @jonbloom
 - A bug was introduced by #28 and has been fixed.

### 2021-09-23:
 - New images are based on Alpine 3.14 *** IMPORTANT ***
   - If this container stops to work after you upgrade, please read this: [https://docs.linuxserver.io/faq](https://docs.linuxserver.io/faq)
 - We are working in a new image: HA-ADDON! Thanks to @AnthonyPluth ! Stay tuned for news about it!

### 2021-09-13:
 - A new configuration parameter has been added: *verbosity*
 - Environment variable *DEBUG* has been renamed to *LISTEN_ONLY* to prevent confusion
 - Better error handling and output (still work in progress)

### 2021-09-09
  - Added last Will and testment messages
  - Added availability status topic
  - Added RTL_MSGTYPE to debug mode

### 2021-09-03
  - Added DEBUG Mode
