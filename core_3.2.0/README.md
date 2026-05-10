Для використання нових бібліотек в Arduino 1.8.19 з ядром 3.2.0

для ESP32-S3: 
треба взяти 
..esp32s3\libesp_netif.a 
..esp32s3\liblwip.a 
та замінити ними файли в директорії: 
C:\Users\User\AppData\Local\Arduino15\packages\esp32\tools\esp32s3-libs\3.2.0\lib

для ESP32 WROOM, ESP32 WROVER: 
треба взяти 
..esp32\libesp_netif.a 
..esp32\liblwip.a 
та замінити ними файли в директорії: 
C:\Users\User\AppData\Local\Arduino15\packages\esp32\tools\esp32-libs\3.2.0\lib


При використанні Visual Studio Code, 

для ESP32-S3: 
скопіювати файли 
..esp32s3\libesp_netif.a 
..esp32s3\liblwip.a 
в папку: 
C:\Users\User\.platformio\packages\framework-arduinoespressif32-libs\esp32s3\lib\

для ESP32 WROOM, ESP32 WROVER:   
скопіювати файли 
..esp32\libesp_netif.a 
..esp32\liblwip.a 
в папку: 
C:\Users\User\.platformio\packages\framework-arduinoespressif32-libs\esp32\lib\

-- шляхи можуть відрізнятися --
