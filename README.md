# Setting-Bluetooth-Devices-on-Linux


# bluetoothctl
[bluetooth]# list
Controller <controller mac> BlueZ 5.5 [default]
[bluetooth]# select <controller mac>
[bluetooth]# power on
[bluetooth]# scan on
[bluetooth]# agent on
[bluetooth]# devices
Device <mouse mac> Name: Bluetooth Mouse
[bluetooth]# pair <mouse mac>
[bluetooth]# trust <mouse mac>
[bluetooth]# connect <mouse mac>

Reference: https://wiki.archlinux.org/index.php/bluetooth_mouse
