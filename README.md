# LSC SmartDimmer (Tuya/BK7231)
Original resources for LSC SmartDimmer based on WB3S WiFi/BT chip.

original_fw.bin is a dump of the original firmware of the device, dumped using [uartprogram](https://github.com/OpenBekenIOT/hid_download_py) from the OpenBeken project.
The unpacked_firmware directory contains the unpacked (decrypted) firmware
The .txt files contain serial logs from the WB3S chip
UART_capture.sr is a PulseView archive containing serial communication between the anonymous IC and WB3S during various actions (rotate up/down, rotate fast, click, pair, etc).
