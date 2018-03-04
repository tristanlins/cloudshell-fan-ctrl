CloudShell fan control script
=============================

A simple fan control script for [CloudShell](http://www.hardkernel.com/main/products/prdt_info.php?g_code=G150575879656) to reduce noice.

Depending on the processor and hard disk temperature, the fan is turned on or off.
The script uses an upper and lower temperature value. This prevents on / off hopping of the fan.

| Action    | CPU temp | SDA temp | SDB temp |
| --------- | -------- | -------- | -------- |
| start fan | > 70°C   | > 55°C   | > 55°C   |
| stop fan  | < 55°C   | < 35°C   | < 35°C   |

Depending on the load and the environment, these values should be adjusted to avoid permanent damage!

