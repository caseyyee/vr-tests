# vr-tests

A collection of example tests for WebVR.

### Setting opacity on preserve-3d elements causes incorrect rendering.
  * http://caseyyee.github.io/vr-tests/cssvr-opacity.html
  * image: http://caseyyee.github.io/vr-tests/cssvr-opacity/bug.jpg
  * bugzilla: https://bugzilla.mozilla.org/show_bug.cgi?id=1182713

### Hit testing of elements must only hit elements in front of the camera
  * 360deg example: http://caseyyee.github.io/vr-tests/elementFromPoint-360deg.html
  * 180deg example: http://caseyyee.github.io/vr-tests/elementFromPoint-180deg.html
  * Image: http://caseyyee.github.io/vr-tests/elementFromPoint-360deg/bug.gif
  * bugzilla: https://bugzilla.mozilla.org/show_bug.cgi?id=1171756

  Elements that have been returned by elementFromPoint are highlighted in grey.

### Allow Iframe to be used as "portal" into another 3d world/view
  * http://caseyyee.github.io/vr-tests/cssvr-into-iframe.html
  * Image: http://caseyyee.github.io/vr-tests/cssvr-into-iframe/bug.png
  * bugzilla: https://bugzilla.mozilla.org/show_bug.cgi?id=1171764
