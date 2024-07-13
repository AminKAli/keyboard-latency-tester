Test setup:

- Host: Raspberry Pi 4 running Raspberry OS version 12
- Keyboard: MDBT50Q-RX board as a 1 key keyboard running Experimental fork of ZMK https://github.com/AminKAli/zmk/tree/experimental-dongle-llpm-esb
    - All tests were done with a secondary MDBT50Q-RX connected to the RPi4 via USB to allow using nordic's propriatery protocols
    - ble_llpm: testing Nordic's Low Latency Packet Mode (LLPM)
    - esb_dpl: testing Nordic's Enhanced Shock Burst (ESB) with a dynamic payload size
    - esb_static: testing Nordic's Enhanced Shock Burst (ESB) with a static payload size
