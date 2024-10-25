# CoryDora

A fully open-source, RP2040-based, QMK-compatible 3x3 mechanical macropad!

## How to customize your CoryDora?

Thank you for getting a CoryDora! To get started,
1. Plug your CoryDora to your comuter using a Type-C cable
2. To customzie your keys + macros, open [Via in your web browser](https://usevia.app/design) that supports [WebHID](https://caniuse.com/webhid) (Chrome, Opera, Edge, etc.) and click "Authorize Device"
3. Download this [json file](https://raw.githubusercontent.com/balub/qmk_firmware/refs/heads/master/keyboards/handwired/corydora/via.json), this is the configuration of CoryDora for Via, onto your computer
4. (Upload the JSON file to Via)[https://www.youtube.com/watch?v=KnYtOmdbHmA]
5. Have fun! You can now customize your CoryDora as you'd like!

## Rationale

Whether you're automating scripts, controlling your media, or just jazzing up your desk setup, CoryDora brings a playful and productive twist to your workspace!

Control media, setup scripts, write macros and if you discover interesting hacks, send them to us :)

Designed, manufactured and assembled with ❤️ in Bengaluru, India.

-

Get yourself a CoryDora at [shop.absurd.industries](https://shop.absurd.industries/products/cory-dora)!

<p align="center">
<img src="img/cory-dora-deku-shopabsurdindustries-534888.webp" alt="CoryDora v1" width="600"/>
<img src="img/cory-dora-deku-shopabsurdindustries-519762.webp" alt="CoryDora v1" width="600"/>
</p>

## Features:

- Easy to source and build components
- Hot swappable switches
- QMK compatible
- OLED 0.91" screen
- Rotary encoder with click-support
- Completely open-source

## Parts list
**Part**|**Quantity**|**Link to buy online**
:-----:|:-----:|:-----:
 Hotswap Sockets|9|https://stackskb.com/store/ttc-pokayoke-hotswap-sockets-v2-10000-cycles
 Through hole 1N4148 Diode|9|https://stackskb.com/store/1n4148-through-hole-diode
 RP2040 zero|1|https://robu.in/product/waveshare-rp2040-zero-without-header
 Rotary Encoders|1|https://robu.in/product/m274-360-degree-rotary-encoder-module-brick-sensor/
 0.91 inch I2C OLED display|1|https://robu.in/product/0-91-inch-128x32-i2c-iic-serial-oled-lcd-display-modulewith-gn
 Mx compatible mechanical switches|9|https://stackskb.com/product-category/switches/linear/

## Firmware

Clone [forked QMK](https://github.com/balub/qmk_firmware) repositories and set up the build environment. See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

<img src="img/qmk-badge-dark.png" alt="QMK" width="145"/>
