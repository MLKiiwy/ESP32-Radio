# Fork of [ESP32-Radio](https://github.com/Edzelf/ESP32-Radio)

This project is ready to be use with platform.io instead of Arduino.

It will replace / enhance the project: https://github.com/MLKiiwy/vintage-webradio

## Why?

- faster to boot
- less power usage
- rely on an existing project
- more debug tools + a small display

## Change

- The project is actually using a [VS1003/VS1053 card](https://fr.aliexpress.com/item/32956293891.html?spm=a2g0s.9042311.0.0.576f6c37jCH8yX)  instead of a [VS1053 only card](https://fr.aliexpress.com/item/32965676064.html?spm=a2g0o.productlist.0.0.78df4253If8bK3&algo_pvid=30f14fdd-d91a-427f-a696-4d16c177ce79&algo_expid=30f14fdd-d91a-427f-a696-4d16c177ce79-17&btsid=2100bde716041698085237831e3e34&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_). It's temporary. Please change the source code line 958 of Esp32_radio.ino

## Hardware

- 1 [ESP32 "Expressif WROOM-32D"](https://fr.aliexpress.com/item/4000296658456.html?spm=a2g0s.9042311.0.0.576f6c37jCH8yX) - 5 Euros
- 1 [Ecran OLED 128x64 I2C](https://fr.aliexpress.com/item/33060125669.html?spm=a2g0s.9042311.0.0.576f6c37jCH8yX) - 2 Euros
- 2 [Rotary encoder](https://fr.aliexpress.com/item/32864246557.html?spm=a2g0s.9042311.0.0.27426c37XIycFz) - 2x0.5 Euros = 1 Euro
- 1 LED 3 colors
- 1 [VS1053](https://fr.aliexpress.com/item/32965676064.html?spm=a2g0s.9042311.0.0.37e26c37Sjl6ef) - 6 Euros

## Bonus (in future version)

If possible let's try to use the real FM radio !

Use an [Si4703 Tuner FM](https://fr.aliexpress.com/item/32412451595.html?spm=a2g0s.9042311.0.0.37e26c37Sjl6ef) - 2 Euros