Are you agree on statement "We can't create key logger in Java". I know most of you say this statement is correct. Because we know that Java can't read anything outside of JVM (Java Virtual Machine). Even I was thinking same but my colleague was searching on the same. He found API called jNativeHook which makes it happen..

jNativeHook Features
Global Keyboard Listener
Global Mouse Listener
Global Mouse Wheel Listener

How it manage to capture key strokes from other application or anywhere in system?
Well jNativeHook using other programming language to capture key strokes and pass it to your application. Its using

.dll (Dynamic Link Library) for windows.
.dylib (Xcode Dynamic Library) for mac
.so (Shared object) for linux


Known Issues
The library does not receive events after waking from a sleep state on Unix/Linux.
Users on Windows may experience a lapse in event data while using Remote Desktop in full screen mode.

Useful Links
Download API: https://code.google.com/p/jnativehook/downloads/list
Examples: https://code.google.com/p/jnativehook/wiki/examples

Check out jNativeHook project home page for more information and details
