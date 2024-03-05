# BB9900-USB_BLE_Keyboard
## About this Keyboard

This mini Keyboard uses the original Blackberry 9900 keyboard with Trackpad and powered by the NRF52840 Microcontroller and operates under modified ZMK Firmware.  

Brief Video of using this tiny keyboard:  

Here are some **main Features:**  
**Processor**: [NRF52840](https://www.nordicsemi.com/products/nrf52840) from Nordic Semiconductor  
**Firmware**: Modified ZMK Firmware.  
**Swapable battery Design**: Replace your battery in 10 seconds.  
**Battery type**: Nokia BL-5B.  
**Long battery life**: The keyboard can work more than 3 months when normally used without recharging.  
**Mouse and scroll wheel 2 in 1**: When enable Capslock, the trackpad works as scroll wheel.  
**Compatible with all platform**: Android, Apple, Windows, Linux as long as your device has Bluetooth modul.  
**On board charging circuit**: The USB-C port can not only be used for data transmitting but also can be used for charging battery  
**USB&BLE Output**: Support both wired and wireless connect.  
**Shoulder keys**: There are two shoulder keys on top side of the keyboard which can be used as mouse left and right keys.  
**Multidevice connect**: The keyboard can be connected up to 4 devices at the same and can be switched between them easily.

## Before you buy/use

**Bluetooth version check**: This keyboard can only be paired wirelessly with devices that have **BLE 5.0 modul or higher**, please check if your device have the right Bluetooth modul, otherwise the keyboard can not work with your device wirelessly!  
How to check the Bluetooth version of your device: google (your device name) like iphone 8 and plus Bluetooth version and you will find the answer like this:
 <img src="https://github.com/ZitaoTech/BB9900-USB_BLE_Keyboard/blob/main/Pics/BLE%20VERSION%20check.png" width = "400" height = "200" alt="BLE VERSION CHECK" align=center />

**About the battery**: If you want to buy the keyboard, **you will need to buy the battery yourself** because of the [shipping policy of Lithium battery](https://www.dhl.de/en/toolbar/footer/informationen/gefahrgut.html) from DHL. The Battery type that you need to buy is **BL-5B**. You can first check if you can buy it on your local Amazon or ebay webside. If there is not, you can buy the battery on Aliexpress. **Just buy the cheapest one**, in Europe the cheapest one will cost approximaltely 6 Euros. Here are some pictures of the battery price from Amazon, ebay and Aliexpress:  
 <img src="https://github.com/ZitaoTech/BB9900-USB_BLE_Keyboard/blob/main/Pics/BL-5B%20on%20Amazon.png" width = "322" height = "225" alt="BL-5B on Amazon" align=center />
 <img src="https://github.com/ZitaoTech/BB9900-USB_BLE_Keyboard/blob/main/Pics/BL-5B%20on%20ebay.png" width = "334" height = "225" alt="BL-5B on Ebay" align=center />
 <img src="https://github.com/ZitaoTech/BB9900-USB_BLE_Keyboard/blob/main/Pics/BL-5B%20on%20Aliexpress.png" width = "240" height = "136" alt="BL-5B on Ebay" align=center />

## Where to buy

**Pay with dollar**: Tindie  
**Pay with Euro**: Lectronz  

# How to use this keyboard  
## Concept of Layer
Because of the limited number of keys on this tiny keyboard, there are many normal keys like characters or symbols and media keys that we want the keyboard to type out. By default I have set 3 layers on this keyboard, by pressing the layer toggle keys we can enter and exit the layer, at the same time the backlight under the 4 big button keys work as indicator for the current layer number. You can find more Information about it under **Backlight Control**  
When we power the keyboard on, we are at Layer 1: the QWERTY layer. By pressing the sym key on the right under area, we can enter Layer 2: now we can type out symbol and number like # 1 2 3 which is originally marked on the keyboard. The Layer3 contains some Bluetooth operation keys and other symbols.  

## Keymap
The following pictures show the default keymap of the keyboard

## What to do when you first get this keyboard  
Here are a few steps to connect the keyboard with your device when you first get hands on this keyboard:  
1. Put the battery into the keyboard: The pictures shows you how to correctly put the battery into the keyboard.  
2. Power the keyboard on by sliding the red switch to the right side:  
3. You can see the backlight under the keyboard area is turned on, press the aA key on the right under area to enter layer 3 and you can see the backlight under the pannel for the 4 big buttons starts to breath.
4. Press the fitst big button on the left and double tap the trackpad: Now the keyboard has cleared the early pairing informations and is ready to pair with a new device. For the keyboard, this device is remember as device 1.  
5. Check the Bluetooth setting on your device and pair with the kaybord and now you can type with the keyboard.

## Multiconnect  
The keyboard can be paired with up to 4 devices and can be switch between them very quickly.  
Here are a few steps showing how you connect the keyboard with a new device when you have already paired with a first device:  
1. Enter Layer 3 by pressing the aA key on the right under area and you can see the backlight under the pannel for the 4 big buttons starts to breath.
2. Press the second or third or fourth big button key dependen on which number you want the keyboard to remember.
3. Double tap the trackpad to clear the early pairing information to make sure it is now pairing with a new device.
4. Operate on you device to pair with the keyboard
5. If you want to switch to another device, enter layer 3 and press the big button that is match with your early operation, **don't double tap the trackpad this time.**

## How to delete the pairing  
If you don't want the keyboard to connect with some device that you paired before, here are a few steps that you should do to delete the pairing:  
1. On the keyboard side: switch to the device that you want to delete by entering layer 3 and press the right big button.
2. Go to the Bluetooth setting page of the device and delete the Bluetooth pairing with the keyboard.
3. Now on the keyboard side: Enter Layer 3 and double tap the trackpad to delete the pairing information that is stored in the keyboard.  
**In brief, if you want to delete the pairing, make sure to operate on both sides that the pairing information is deleted.**

## USB&BLE Output select
This keyboard supportes both USB and BLE output, here are some basic logics of the output select:  

By default, output is sent to BLE when both USB and BLE are connected.  

If the keyboard wasn't connected to any device or is out of the communication distance with a paired device, the output would be USB.  

Once you toggle the output between USB and BLE by entering layer 3 and hold space key for more than a half second. The keyboard will remember this if you don't make any change for more than 10 seconds.

## Backlight/LED control  
There are 4 LED controls on this keyboard:  
1. Charging LED: the read led on the left side of the keyboard indicates if the battery of the keyboard is fully charged. When the battery is being charged, the light shows like this. When the battery is fully charged, the led will go out.  
2. Keyboard backlight: When you power the keyboard on, the backlight of the QWERTY keyboard area will be turned on immediately. If the keyboard doesn't detect any key press for more than 30 seconds, the backlight will be turned off. Also the brightness of the backlight can be manuelly set. You can find the related action on layer 3. The brightness of the keyboard backlight is set at 40% by default. The brightness adjustment step  in percent is 10%.  
3. Big button backlight: The backlight of this area works as indicator of the current number of layer. At Layer 1, the backlight is turned off. At Layer2, the backlight is turned on. At Layer3, the backlight starts to breath.  
4. Trackpad backlight: The backlight of the trackpad works as indicator of capslock. When capslock is on, the backlight will be turned on and also the trackpad will work as scroll wheel. You can now sweep your finger on the trackpad to quickly browse a webpage or file.  

# Playing tricks with this keyboard
