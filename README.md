# scrollmash
scrollmash bind for blue fire

code used:
--------
#singleinstance force
~WheelUp::
if WinActive("Blue Fire") {
send {LButton down}
send {LButton up}
}
return

~WheelDown::
if WinActive("Blue Fire") {
send {LButton down}
send {LButton up}
}
return
