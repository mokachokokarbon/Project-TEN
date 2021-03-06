CHANGELOG
---

**Patch 0.5**

_Release Date: 6 Apr 2019 (latest)

* Upgrade
    * keyboard upgraded to 0.13
    * Python upgraded to 3.7.2
    * PyQt upgraded to 5.11.3

* UI
    * Improved the looks of the timer label

* Bug fixes
    * Fix crash when customizing a shortcut

* Things to implement in the next version (v0.6)
    -[ ] Timer slows down when the height of the LCD display increases [#3](https://github.com/jerobado/Tenny/issues/3)


**Patch 0.4**
    
_Release Date: 1 Nov 2017_ 

* Highlight(s)
    * Added `Ctrl+Q` as default shortcut to easily quit the timer without navigating into the notification area
    * Restrict the user on entering existing hotkeys to eliminate hotkey conflict [#4](https://github.com/jerobado/Tenny/issues/4)

* License
    * Added GNU GPLv3 as license for Tenny

* Upgrade
    * Python upgraded from 3.5.2 to **3.6.3**
    * PyQt upgraded from 5.8.1 to **5.9.1**  


**Patch 0.3**

_Release Date: 1 Jul 2017_

* Highlights
    * User can now set his/her preferred shortcuts keys to control the timer.
    * Tenny is now accessible and controllable in the notification area.
    * Window opacity is now adjustable.

* Behavior 
    * Tenny will still run in the background if the window is closed. It can only be close in the notification area. 

* User Interface (UI)
    * Last known position and size of the window is now retrieved upon re-opening the app.


**Patch 0.2**

_Release Date: 1 Jun 2017_

* Highlight
    * Added hotkey support.
    
* User Interface (UI)
    * Can now be resize.
    * Added stopwatch icon in the taskbar.
    * Added tooltip in the Start/Stop and Reset buttons.


**Patch 0.1**

_Release Date: 16 Mar 2017_

* Feature
    * With `START`, `STOP` and `RESET` button to control the timer.
    * Semi-transparent and fixed window size.
    * Always on top.
    
    