LeapScroll
==========

Simple Javascript bookmarklet to enable Leap Motion controller based scrolling


After loading some web page that you want to scroll through just click the bookmark and you can use your Leap Motion controller to scroll. Note, this requires (and loads) the Leap Javascript library from: http://js.leapmotion.com/ I started with code from here: http://garage-interactive.com/leapbookmarklet/ which is out of date. *** Only tested in Chrome!

Features:
 - Using more fingers scrolls faster.
 - There is a small neutral zone (from 90mm to 125mm above)
 - The scroll zone is low enough to the device to allow resting your (my) wrist on the table in front of the device
 - Above 325mm is a zone that scrolls up extra faster
 - Scrolling should only work when the window (javascript document) "has focus".
 - Multiple fingers (even across multiple hands) at multiple heights can all contribute to the scrolling rate.

