## Microsoft Spy++

Spy++ is a Win32-based utility that gives you a graphical view of the system’s processes, threads, windows, and window messages.

Spy++ lets you perform the following tasks:

 - Display a graphical tree of relationships among system objects. These include processes, threads, and windows.

 - Search for specified windows, threads, processes, or messages.

 - View the properties of selected windows, threads, processes, or messages.

 - Select a window, thread, process, or message directly in the view.

 - Use the Finder Tool to select a window by mouse pointer positioning.

 - Set message options by using complex message log selection parameters.
    
# Find out what process registered a global hotkey? (Windows API)
https://stackoverflow.com/questions/829007/find-out-what-process-registered-a-global-hotkey-windows-api
<img src="https://devnullproxy.webnode.com/_files/200000387-9c8ad9c8af/Annotation%202020-07-22%20150557.png">
###### #note that the 64-bit version of Spy++ catches only messages for 64-bit applications, so if you don't see the WM_HOTKEY message in the Message log after pressing the hotkey, you may need to run the 32-bit version of Spy++


* if it is the AltGr+M (or Ctrl+Alt+M) that is not working for you, than it might be due to `NvidiaExperience` settings.
```
Nvidia Experience -> Settings -> Keyboard shortcuts -> disable/remap mic toggle
```
<img src="https://devnullproxy.webnode.com/_files/200000388-34afc34aff/image.png">
