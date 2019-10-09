# Web Audio API Chrome Bug

This simple projects a bug in Chrome for the Web Audio API where multiple channels are rearranged.

## Environment

Operating System: MacOS 10.15 (19A583)
Browser: 
    * Chrome 77.0.3865.90 (Official Build) (64-bit)
    * Firefox 69.0.2 (64-bit)

## Steps to reproduce
* Visit the test URL with Firefox
* Play audio
* Check channel order in peak meter
* Do the same steps again with Chrome

## Actual Result
Channels are not in correct in Chrome but in Firefox

## Expected Result
Channels are in same order as in Firefox
