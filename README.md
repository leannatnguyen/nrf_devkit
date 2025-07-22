# nrf_devkit

## SDK Setup

1. Clone this repo:
   ```bash
   git clone https://github.com/leannatnguyen/nrf_devkit.git
   cd nrf_devkit/ncs
2. Init and update the SDK:
    ```bash
    west init -l .
    west update
3. Build
    ```bash
    west build -b nrf52840dk_nrf52840 ../app
4. Flash
    ```bash
    west flash
