# Setting-Bluetooth-Devices-on-Linux


bluetoothctl <br>
[bluetooth]# list <br>
Controller <controller mac> BlueZ 5.5 [default] <br>
[bluetooth]# select <controller mac> <br>
[bluetooth]# power on <br>
[bluetooth]# scan on <br>
[bluetooth]# agent on <br>
[bluetooth]# devices <br>
Device <mouse mac> Name: Bluetooth Mouse <br>
[bluetooth]# pair <mouse mac> <br>
[bluetooth]# trust <mouse mac> <br>
[bluetooth]# connect <mouse mac> <br>

Reference: https://wiki.archlinux.org/index.php/bluetooth_mouse
