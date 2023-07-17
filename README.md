# ESP-XToys-custom
Simple way to make your own ESP toys for XToys.app with ESPHome platform

Compile and upload the firmware using ESPHome with provided yaml configuration file.

But before that, change the parameters to match your network settings.

In XToys.app Custom Toys create new MQTT Toy and fill parameters:
- Name: \<\<Name of your chosing\>\>
- Type: 1 Channel Vibrator
- NR of intensity steps: 100
- MQTT address: wss://\<\<your MQTT domain\>\>:\<\<MQTT secured websocket port\>\> for ex. wss://services.paxy.in.rs:8083
- Credentials required: Yes
- MQTT publish topic: xtoys/fm (or anything else).
- Message payload: \<\<vibrate\>\>
