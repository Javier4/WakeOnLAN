# WakeOnLAN 2.11.4
## Beta 10 - _November 1 2015_

* Fix "Object reference not set" error on certain users.


# WakeOnLAN 2.11.3

## Beta 20 - _June 5 2015_

* Fixed a missing dependency that caused the "print" function to crash.

## Beta 10 - _May 26 2015_

* Groups are now sorted alphabetically
* added command-line option to gui program to load an alternate machines database file.
  You can create a shortcut, and in the target, force it to load another database.
  Example: WakeOnLan.exe -p "\\\\aquila\\files\\Users\\phil\\My Documents\\machines.xml"

# WakeOnLAN 2.11.2

## Beta 25 - _April 14 2015_

* French updates
* Added Spanish translation
* Added task tray options for RDP and Shutdown of hosts

## Beta 10 - _April 8 2015_

* Fix problems with auto updater.


# WakeOnLAN 2.11.1

## Beta 10 - _Mar 30 2015_

* Russian language updates.


# WakeOnLAN 2.11.0

## Beta 22 - _Mar 27 2015_

* Fix problem with threadpool not pinging every machine in the queue.


## Beta 20 - _Mar 24 2015_

* New installer based on Inno Setup.
* Installer is multilingual.  Installation language carries over to the WOL program.
* New scheduler option to send messages to machines.
* New feature: managed thread pool.  The polling of machines is now managed so that it doesn't overload network.
 You can select how many machines are pinged simultaneously (default is 10).


## Beta 10 - _Mar 12 2015_

* A lot of fixes to popup messaging system.
* Added ability to schedule messages to multiple hosts.


# WakeOnLAN 2.10.19

## Beta 21 - _Mar 5 2015_

* Major code rewrites for the shutdown module, messaging, and properties pages.
* Legacy shutdown and reboot modes now supported in command-line and scheduler.

![Properties](https://sourceforge.net/p/aquilawol/discussion/1105198/thread/d64df5ff/e64c/attachment/Capture.PNG)

------

## Beta 15 - _Mar 3 2015_

* Shutdown for Workgroups.  To use this, open properties for the host you want to shutdown.
Click on "Password".  Enter a userid and password.  You can leave the domain blank.
Click on Shutdown Method, select "Legacy".

## Beta 10 - _Mar 1 2015_

* Testing new ideas for Shutdown on Workgroup type computers.


# WakeOnLAN 2.10.18

## Beta 40 - _Feb 24 2015_

* Enhanced Listener. Now displays more useful data from captured packets.
* Added "Clear-IP" function to main window context menu.  Used to remove IP address from DHCP hosts.

## Beta 35 - _Feb 23 2015_

* Command-line program displays the broadcast subnet on wakeup command.

## Beta 32 - _Feb 20 2015_

* Database path is shared between installer and WOL.
* Can now have a custom DB filename, and it is preserved between versions.
