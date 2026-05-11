Аудіомод для відтворення FLAC без переривань. Працює з ESP32S3 ядром 3.3.6
----

Для використання в Arduino 1.8.19 з ядром 3.3.6 потрібно взяти два файли 

..esp32s3\libesp_netif.a 

..esp32s3\liblwip.a 

та замінити ними файли в директорії:
~~~~~~~~~~~~~~~
C:\Users\User\AppData\Local\Arduino15\packages\esp32\tools\esp32s3-libs\3.3.6\lib
~~~~~~~~~~~~~~~

При використанні Visual Studio Code, 

для ESP32-S3: 

скопіювати файли 

..esp32s3\libesp_netif.a 

..esp32s3\liblwip.a 

в папку:
~~~~~~~~~~~~~~~
C:\Users\User\.platformio\packages\framework-arduinoespressif32-libs\esp32s3\lib\
~~~~~~~~~~~~~~~

шляхи можуть відрізнятися
