# bare_metal_test

does not find linker script:
mbed compile --profile ./profiles\bootloader.json -m NRF52840_DK --build BUILD_RELEASE -t GCC_ARM --app-config ./mbed_app.json

finds linker script:
 mbed compile --profile ./profiles\bootloader.json -m EFM32PG12_STK3402 --build BUILD_RELEASE -t GCC_ARM --app-config ./mbed_app.json
