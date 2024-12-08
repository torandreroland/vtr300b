# vtr300b 
Simple control of Systemair vtr300b via modbus TCP (Wifi) directly to HA.

This particular project is for Systemair units with old displays featuring a wheel, as shown in this photo:

<img src="https://i.imgur.com/BJba6Vp.png" width=40% height=40%>

Credits to Ztaeyn (newer modbus-codes) and os11k (older modbus-codes):
* https://github.com/Ztaeyn/HomeAssistant-VTR-Modbus
* https://github.com/os11k/vtr200b

With this, you can currently:
- Change operation mode (Low speed, Normal speed, High speed)
- Set the desired temperature on the VTR thermostat.
- View alarm status and filter replacement countdown.

Sources:
* Modbus codes: https://shop.systemair.com/upload/assets/MODBUS_FOR_RESIDENTIAL_D24810_USER_MANUAL_EN__A007_.PDF?91306fe4

NOTE: The addresses have an offset of -1 compared to the VTR user manual above.

My Control Panel is very simple, and the code is in this repository under the `user_interface` folder.

<img src="https://i.imgur.com/kywBMzn.png" width=40% height=40%>
