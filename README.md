# Larduino + PlatformIO  

This project uses the released v3.6c version of the Larduino Arduino core (https://github.com/LGTMCU/Larduino_HSP/files/3333048/Larduino_HSP_v3.6c.zip). 

This is **not** the same as the core version in the Larduino_HSP repository, for some reason (was never updated).

# Choose your board

See https://github.com/maxgerhardt/larduino-pio/tree/master/boards for the list of boards. They are copies of the ones available in Arduino IDE, defined in the `boards.txt`. 

For example for the "Larduino w/ LGT8F328D-SSOP20" board, choose `board = lardu_328s` in the `platformio.ini`. See the boards folder for all boards.

If you want to run at 32MHz, uncomment the line 

```
;board_build.f_cpu = 320000000L
```

in the `platformio.ini`
