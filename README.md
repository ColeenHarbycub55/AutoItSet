# AutoItSet
#RequireAdmin AutoItSetOption('TrayAutoPause', 0) HotKeySet("^+v", 'Sender')  While 1     Sleep(100) WEnd  Func Sender()     Send(ClipGet()) EndFunc
