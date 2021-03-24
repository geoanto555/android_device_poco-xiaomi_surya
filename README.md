# android_device_poco-xiaomi_surya
Source to compile TWRP

![POCO X3 NFC](https://fdn.gsmarena.com/imgroot/reviews/20/poco-x3-nfc/lifestyle/-1024w2/gsmarena_001.jpg "POCO X3 NFC")
Pocophone X3 NFC - twrp
=====================================================
Basic   | Specs
-------:|:-------------------------
CPU     | Qualcomm SM7150-AC Snapdragon 732G (8 nm)
GPU     | Adreno 618
Memory  | 6 GB 8GB
Storage | 64GB / 128GB
Os      | Android 10, MIUI 12
Battery | Li-Po 5160 mAh, non-removable
Dimensions | 165.3 x 76.8 x 9.4 mm (6.51 x 3.02 x 0.37 in)
Display |  6.67 inches 1080 x 2400 pixels
Rear Camera  | 64 MP, f/1.9, (wide), 1/1.73", 0.8µm, PDAF
Front Camera | 20 MP, f/2.2, (wide), 1/3.4", 0.8µm
Release Date |  2020, September 07

## STATUS : STABLE

## Working :

- ADB

- Decryption userdata 

- Screen brightness settings

- Correct screenshot color

- MTP

- Sideload

- vibration

- fastbootd

## To compile

- build/envsetup.sh

- export ALLOW_MISSING_DEPENDENCIES=true

- lunch 

- make -jX recoveryimage
