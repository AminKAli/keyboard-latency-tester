Test setup:

- Host: Raspberry Pi 4 running Raspberry OS version 12
- Keyboard: Seeeduino XIAO Ble board with GPIO 5 wired to a switch running Experimental fork of ZMK https://github.com/AminKAli/zmk/tree/experimental-dongle-llpm-esb
    - All results below were done with a MDBT50Q-RX connected to the RPi4 via USB to act as the receiver/central device
    - ble_llpm: Testing Nordic's Low Latency Packet Mode (LLPM)
    - esb: Testing Nordic's Enhanced Shock Burst (ESB) protocol
    - esb_250usTimeout: Shutting down the HFClock after 250us of inactivity to save power
    - esb_500usTimeout: Shutting down the HFClock after 500us of inactivity to save power
    - esb_1msTimeout: Shutting down the HFClock after 1ms of inactivity to save power
