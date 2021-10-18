# Arctis7_BatteryReader
A battery reader for the Steelseries Arctis7 Wireless Headset. It polls the percentage and displayes it as a tray icon.

It uses the MightyHID Library by twatorowski (https://github.com/MightyDevices/MightyHID). You will have to download and build it and then set this projects Assembly reference to the built 'MightyHID.dll'. Other Assembly references I had to set manually were 'System.Windows.Forms' and 'System.Configuration.ConfigurationManager'.
To build the project I would suggest to use the "Release" configuration (The build configuration can be chosen from a drop-down menu in VS somewhere to the left of the green run-arrow at the top).

After building, the necessary files (including the .exe) can then be found in "SteelSeries_Arctis7_BatteryReader\\bin\\Release\\netcoreapp3.1\\".

Additionally, the Headset_Battery_Icons folder (unzipped) has to be in the same folder as the executable (SteelSeries_Arctis7_BatteryReader.exe).

(Then i copied all contents of the 'netcoreapp3.1' folder including the Headset_Battery_Icons folder into a folder in my Programs folder)


I made all icons myself, so no copyright or smth. If you want to change them, I included the .xcf-file (Gimp 2: i always first exported to png and then only that png to icon).

I put this program into my autostart and it's a real enrichment to using the headset :)
I'm not planning to change anything concerning this project, since it works fine for me. I just wanted to give other people a headstart when trying to accomplish this.

I'm not affiliated with Steelseries in any way and did this as a hobby project.

Have fun!

crazyklatsch
