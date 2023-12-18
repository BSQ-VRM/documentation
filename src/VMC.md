# Virtual Motion Capture


## What could Virtual Motion Capture possibly be used for???
- This mod makes use of the Virtual Motion Capture Protocall to allow for FBT through SlimeVR or other methods that come up in the future.
	- NOTE: FBT still needs more testing and tweaking. If you have a SlimeVR setup and are willing to help I can guide you through setting up. I do not have a kit for myself so it is hard for me to tell if it will look correct in game.


## Sender

#### Available Options
- Enable Sender: This enables sending controller and headset positions over Wi-Fi through the VMC Protocall.
- Destination IP Address: This is the IP address you want to send VMC Protocall data to. This is typically the IP address of your pc or your quest itself if you run SlimeVR through Termux on the Quest.
- Destination Port: This is the port to send data through. Typically `3950`. This is the same value as the `Port In` value in SlimeVR VMC settings.

## Receiver

#### Available Options
- Enable Receiver: This enables receiving tracker/bone positions over Wi-Fi through the VMC Protocall.
- Receiver Port: This is the port you want to receive positions through. Typically `3949`. Same value as the `Port Out` in SlimeVR VMC settings.

## Full Body Tracking

#### Available Options
- Enable FBT: This enables Full Body Tracking (obv).
- Right Knee Tracker: Tracker used for the avatar's right knee.
- Left Knee Tracker: Tracker used for the avatar's left knee.
- Right Foot Tracker: Tracker used for the avatar's right foot.
- Left Foot Tracker: Tracker used for the avatar's left foot.
- Waist Tracker: Tracker used for the avatar's waist.
- Chest Tracker: Tracker used for the avatar's chest.