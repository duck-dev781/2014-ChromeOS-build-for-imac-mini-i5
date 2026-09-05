# 2014-ChromeOS-build-for-imac-mini-i5
for robotics teacher named "Sylvest" and to the puplic

# NOTE
Plug in the USB and turn on the Mac mini while holding the Option (⌥) key.Select EFI Boot to launch your Brunch image.Wait for the screen to light up with the ChromeOS Welcome / Language Selection screen. STOP HERE.On your keyboard, press Ctrl + Alt + F2 (or Ctrl + Alt + Refresh if using a Chromebook keyboard) to open the terminal.Type chronos and press Enter to log in.Type lsblk and press Enter to find the internal drive name (it will likely be sda).Run the installer command: sudo chromeos-install -dst /dev/sdaType yes to confirm the wipe, wait for it to finish, and restart the computer!
