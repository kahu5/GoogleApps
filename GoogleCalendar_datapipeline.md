Calendar Data Pipeline

Apps Script
Originally from: https://www.automatedstuff.com/tutorials/how-to-import-google-calendar-data-into-google-sheets-automatically/
Room Resource
In Google Admin
Google Calendars
Links for viewing or adding calendars:
https://calendar.google.com/calendar/embed?src=
https://calendar.google.com/calendar/render?cid=

Google Sheets
// calendarName = "USA-2-Breakout Room 1 (6)"
var calendarID = "back2back.org_2d35393336363637362d393832@resource.calendar.google.com";
https://docs.google.com/spreadsheets/d/1pKJnUMRHg0WMzcLXfCaXqykdldr5rVLVXoIxaYBMyp4

// calendarName = "USA-2-Breakout Room 2 (6)"
var calendarID = "back2back.org_3632353332333731363834@resource.calendar.google.com";
https://docs.google.com/spreadsheets/d/1BH-reTD3tByq-DTz0qr0n3I4vAp-mbHqTKU7I1yQm78

// calendarName = "USA-2-Breakout Room 3 (6)"
var calendarID = "back2back.org_3238363238333636@resource.calendar.google.com";
https://docs.google.com/spreadsheets/d/1swzvJjQdM2VL7XzhLZuzYpFRtiGkLQ64j9pElW7hKPo

// calendarName = "USA-2-Breakout Room 4 (8)"
var calendarID = "back2back.org_33303232373135343334@resource.calendar.google.com";
https://docs.google.com/spreadsheets/d/1E-Kzxq_qdSQz_7s4p3hCauJPCATkq_QjkIbyAbAPFKk

// calendarName = "USA-2-Phone Booth 1 (2)"
var calendarID = "c_188bssopnd75mhp5kktj6coht9sn4@resource.calendar.google.com";
https://docs.google.com/spreadsheets/d/1vcHGQufBMQkrX3bRmnxH1lr8Tw5LfrJDsQxf0NR6SzI

// calendarName = "USA-2-Phone Booth 2 (2)"
var calendarID = "c_1883dmvi5ugqei2rjlnm56770ve16@resource.calendar.google.com";
https://docs.google.com/spreadsheets/d/1ZLqKH3iJLX56Dg_dA0_MzsfN2_cpikP2g1mPNfzD9ck

// calendarName = "USA-1-Training Room (55)"
var calendarID = "back2back.org_3232333833303430393538@resource.calendar.google.com";
https://docs.google.com/spreadsheets/d/16GTYm8tIkljH6N8SillkMQRoPWcSQ_SkWzId1g74Mzc

// calendarName = "USA-2-Fishbowl (12)"
var calendarID = "back2back.org_3639363330373134313334@resource.calendar.google.com";
https://docs.google.com/spreadsheets/d/1cxtM2-MlfAYRGUMPDu_oPmGvM0_T0GxAcG9ak2LqGfs

// calendarName = "USA-2-Studio Conference Room (40)"
var calendarID = "c_1888j3su4j98ui2ti6ls7ahjntbig@resource.calendar.google.com";
https://docs.google.com/spreadsheets/d/10WtYBe47XCPg_24vVa5kzXAyB4ysXEq-G2-nIbi4QBA

Collected through QUERY and IMPORTRANGE:
https://docs.google.com/spreadsheets/d/10OtKNBkn9yHG_bLCIm6k3hUEAJNpDX39UyF_k9GxpBI

=QUERY({IMPORTRANGE("https://docs.google.com/spreadsheets/d/1pKJnUMRHg0WMzcLXfCaXqykdldr5rVLVXoIxaYBMyp4", "Sheet1!A2:Q25"); IMPORTRANGE("https://docs.google.com/spreadsheets/d/1BH-reTD3tByq-DTz0qr0n3I4vAp-mbHqTKU7I1yQm78", "Sheet1!A2:Q25"); IMPORTRANGE("https://docs.google.com/spreadsheets/d/1swzvJjQdM2VL7XzhLZuzYpFRtiGkLQ64j9pElW7hKPo", "Sheet1!A2:Q25"); IMPORTRANGE("https://docs.google.com/spreadsheets/d/1E-Kzxq_qdSQz_7s4p3hCauJPCATkq_QjkIbyAbAPFKk", "Sheet1!A2:Q25"); IMPORTRANGE("https://docs.google.com/spreadsheets/d/1vcHGQufBMQkrX3bRmnxH1lr8Tw5LfrJDsQxf0NR6SzI", "Sheet1!A2:Q25"); IMPORTRANGE("https://docs.google.com/spreadsheets/d/1ZLqKH3iJLX56Dg_dA0_MzsfN2_cpikP2g1mPNfzD9ck", "Sheet1!A2:Q25"); IMPORTRANGE("https://docs.google.com/spreadsheets/d/16GTYm8tIkljH6N8SillkMQRoPWcSQ_SkWzId1g74Mzc", "Sheet1!A2:Q25"); IMPORTRANGE("https://docs.google.com/spreadsheets/d/10WtYBe47XCPg_24vVa5kzXAyB4ysXEq-G2-nIbi4QBA", "Sheet1!A2:Q25"); IMPORTRANGE("https://docs.google.com/spreadsheets/d/1cxtM2-MlfAYRGUMPDu_oPmGvM0_T0GxAcG9ak2LqGfs", "Sheet1!A2:Q25")}, "where Col1 <>''")
Google DataStudio
https://datastudio.google.com/reporting/a72867e2-b8d7-45d7-856f-bb8c5227f9e1

Firebase Dynamic URL
https://console.firebase.google.com/project/

Devices
Raspberry Pi WiFi:
/etc/wpa_supplicant/wpa_supplicant.conf
B2BIoT:kdsf7$Sr
Add: scan_ssid=1

Setup a Raspberry Pi to run a Web Browser in Kiosk Mode

ChromeOS:

Turn off touch display on Chrome browser:
Launch the Chrome browser and type the following path:
chrome://flags/#ash-debug-shortcuts
Locate the debugging keyboard shortcuts and click Enable. Disable is selected by Default.
Select the Relaunch Now icon to restart Chrome to apply the changes.
After logging in again, perform this keyboard shortcut.
Search+Shift+t
This allows a way to toggle the touch screen on or off.
Raspberry Pi to USB MIMO  Displaylink Screens

Using Raspberry Pi 3 USB Monitors & Displays
Other USB monitors: DisplayLink USB Single Monitor on Linux 
[other resources: 
https://archive.plugable.com/2009/11/16/setting-up-usb-multiseat-with-displaylink-on-linux-gdm-up-to-2-20/
https://imkiyoung.wordpress.com/2012/09/18/raspberry-pi-and-aoc-e1649fwu-usb-powered-led-monitor/ ] 
Go to directory /etc/X11 and, using your preferred editor, create a file entitled: xorg.conf

Switch screens on lines:
Screen 0 "UGA"
Screen 1 "HDMI" LeftOf "UGA"

Add this to top:
Section "InputClass"
Identifier "MIMO Touchscreen"
MatchIsTouchscreen "on"
Option "Ignore" "on"
EndSection

Add Chrome extensions:
https://chrome.google.com/webstore/detail/keep-awake/bijihlabcfdnabacffofojgmehjdielb
https://chrome.google.com/webstore/detail/page-refresh/hmooaemjmediafeacjplpbpenjnpcneg

Prevent Chrome “restore” popup
chrome://flags/#infinite-session-restore

Auto-start Chrome:
sudo nano /etc/xdg/lxsession/LXDE-pi/autostart
@xset s off 
@xset -dpms 
@xset s noblank 
@chromium-browser --start-fullscreen https://datastudio.google.com/reporting/a72867e2-b8d7-45d7-856f-bb8c5227f9e1/page/p_o8r4rjzumc


Connect remotely to Raspberry Pi:
VNC: Remote access a Raspberry Pi 

