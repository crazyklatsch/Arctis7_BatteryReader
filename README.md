This project is reimplemented in rust and provided with a windows installer in https://github.com/crazyklatsch/Arctis7_BatteryReader_rs

# Arctis7_BatteryReader
A battery reader for the Steelseries Arctis7 Wireless Headset. It polls the percentage every 5 seconds and displayes it as a tray icon.

It uses the MightyHID Library by twatorowski (https://github.com/MightyDevices/MightyHID). You will have to download and build it and then set this projects Assembly reference to the built 'MightyHID.dll'. Other Assembly references I had to set manually were 'System.Windows.Forms' and 'System.Configuration.ConfigurationManager'.
To build the project I would suggest to use the "Release" configuration (The build configuration can be chosen from a drop-down menu in VS somewhere to the left of the green run-arrow at the top).

I included a build manual (Arctis7_BatteryReader_Build_Manual.pdf). If you follow that, you should get it to work.

I made all icons myself, so no copyright or smth. If you want to change them, I included the .xcf-file (Gimp 2: i always first exported to png and then only that png to icon).

I put this program into my autostart and it's a real enrichment to using the headset :)

I'm open for ideas to improve this project.

I'm not affiliated with Steelseries in any way and did this as a hobby project.

Have fun!

crazyklatsch
