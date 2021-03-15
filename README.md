# Setup Arduino for ESP32
## add esp32 package index
![image](https://user-images.githubusercontent.com/22662559/111141117-71b79a00-8583-11eb-813b-38e3471a8e0c.png)

add https://dl.espressif.com/dl/package_esp32_index.json in Addiotional Boards Manager URLs
## add esp32 to board manager (Tools->Board->Boards Manager)
![image](https://user-images.githubusercontent.com/22662559/111141402-cf4be680-8583-11eb-8029-efafe434fd0a.png)

![image](https://user-images.githubusercontent.com/22662559/111141437-dc68d580-8583-11eb-86a9-344336053dc1.png)

## change target to TTGO T-Watch (Tools->Board->ESP32 Arduino->TTGO T1
![image](https://user-images.githubusercontent.com/22662559/111141892-5600c380-8584-11eb-9dd0-28670c1e5426.png)

## Download the T-Watch library as zip
Link: https://github.com/Xinyuan-LilyGO/TTGO_TWatch_Library

![image](https://user-images.githubusercontent.com/22662559/111142303-d0314800-8584-11eb-8115-c179002014a0.png)

## Add the library to Arduino IDE

![image](https://user-images.githubusercontent.com/22662559/111142505-0e2e6c00-8585-11eb-991c-efdb70608bd2.png)

## Connect the Watch to USB and select /tty/USB0 device

![image](https://user-images.githubusercontent.com/22662559/111142747-52217100-8585-11eb-97f3-911109c895b2.png)

## Run the Simple Watch example

File->Examples->TTGO TWatch Library->LVGL->Simple Watch

![image](https://user-images.githubusercontent.com/22662559/111142868-73825d00-8585-11eb-96f3-fb714b9484d6.png)

Modify config.h to include the type of device #define LILYGO_WATCH_2020_V1 

Veriry and Upload
