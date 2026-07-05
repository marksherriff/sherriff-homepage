---
title: "SFXBox Manual v1.0"
sitemap: false
permalink: /sfxbox/
layout: splash
---

# SFXbox User Guide v1.0

The **SFXbox** is a small sound-effects system for Black Box Players productions. It plays sound effects through the theater sound board or a supplemental speaker using the Stream Deck, Logitech presenter remote, numeric keypad, or backup keyboard.

This guide is written for show operators and volunteers. No technical knowledge is required for normal use.

---

## 1. Components

The SFXbox system includes the following pieces:

![Full SFXbox system layout](/sfxbox/images/sfxbox-fullsystem.png)

### Main components

- **SFXbox** — the small black box labeled `Black Box` and `SFXBox`.
- **Stream Deck** — the small button panel with labeled sound-effect buttons.
- **Logitech presenter remote** — the handheld remote with arrow buttons.
- **Wireless numeric keypad** — backup control device.
- **Wireless keyboard** — backup/setup keyboard.
- **USB audio adapter and audio cables** — used to send sound to the sound board.
- **Power adapter and power cable** — used to power the SFXbox.
- **HDMI cable and monitor** — only needed for troubleshooting or updates.

![Stream Deck, remote, numpad, and cables](/sfxbox/images/usb-streamdeck-sound-clicker-numpad.png)

### SFXbox ports and connections

The SFXbox has several ports. For normal show use, the important ones are:

- USB-C power input
- USB ports for the Stream Deck, Logitech receiver, audio adapter, keypad, or keyboard
- HDMI output for a monitor, if troubleshooting is needed
- USB audio adapter output to the sound board

![USB-C power plugged in](/sfxbox/images/usbcpluggedin.png)

![HDMI plugged in for troubleshooting](/sfxbox/images/hdmi-pluggedin.png)

When the SFXbox has power, the green status light should be on.

![Green power/status light](/sfxbox/images/greenlight-poweron.png)

---

## 2. Set Up Before the Show

1. Place the SFXbox near the sound board or supplemental speaker.

2. Ensure all USB adapters are connected to the SFXbox.

3. Connect the **audio output red cable** to the sound board or supplemental speaker.

   Use the audio adapter and cable shown here:

   ![Audio plug, headphones, and speaker adapter](/sfxbox/images/audioplug-headphonesandspeaker.png)

   The usual setup is:

   ```text
   SFXbox → USB audio adapter → audio cable → sound board input
   ```

4. Plug in the Stream Deck.

   ![Stream Deck](/sfxbox/images/streamdeck.png)

5. Plug in the Logitech receiver for the presenter remote, if it is not already connected.  Power on as needed.

   The Logitech presenter remote looks like this:

   ![Logitech presenter remote](/sfxbox/images/clicker.png)

6. Keep the wireless numeric keypad nearby as a backup.  Power on as needed.

   ![Wireless numeric keypad](/sfxbox/images/numpad.png)

7. Keep the wireless keyboard nearby as a backup/setup device.

   ![Wireless keyboard](/sfxbox/images/sparekeyboard-connectoronback.png)

8. Plug in power to the SFXbox.

9. Wait for the SFXbox to start. This may take a short time.

10. When startup is complete, the system should play the ready sound - a long beep.

---

## 3. Testing Before the Show

Before the house opens, test the SFXbox.

### Test 1: Ready sound

After powering on the SFXbox, confirm that you hear the ready sound through the sound system.

If you do **not** hear the ready sound:

- Check that the SFXbox has power.
- Check that the green status light is on.
- Check that the audio cable is connected to the sound board.
- Check that the sound board channel is on and turned up.

### Test 2: Stream Deck

Press one of the Stream Deck buttons.

![Stream Deck buttons](/sfxbox/images/streamdeck.png)

You should hear the matching sound effect.

### Test 3: Logitech presenter remote

Press one of the buttons on the Logitech remote.

![Logitech presenter remote](/sfxbox/images/clicker.png)

You should hear the assigned sound effect.

### Test 4: Backup numeric keypad

Press a mapped key on the wireless numeric keypad.

![Wireless numeric keypad](/sfxbox/images/numpad.png)

You should hear the assigned sound effect.

### If testing fails

Try the backup devices in this order:

1. Stream Deck
2. Logitech presenter remote
3. Wireless numeric keypad
4. Wireless keyboard

If one device does not work but another does, use the working backup device for the show.

---

## 4. Usage During the Show

During the show, use the SFXbox only as needed for sound effects.

### Stream Deck

The Stream Deck is the primary sound-effect control surface.

![Stream Deck](/sfxbox/images/streamdeck.png)

Each labeled button plays the sound effect shown on that button.

### Logitech presenter remote

The Logitech presenter remote can be used for actor-triggered or operator-triggered cues.

![Logitech presenter remote](/sfxbox/images/clicker.png)

Press the assigned button to trigger the assigned sound.

### Numeric keypad backup

The numeric keypad is a backup control device.

![Wireless numeric keypad](/sfxbox/images/numpad.png)

Use it if the Stream Deck or presenter remote is unavailable.

### During-show reminders

- Do not unplug the SFXbox during the show.
- Do not unplug the Stream Deck during the show unless instructed.
- Do not change cables during the show unless troubleshooting is necessary.
- If one control device fails, try another control device.
- If no sound is heard, check the sound board channel first.

---

## 5. Putting It Away After the Show

After the show:

1. Stop using the SFXbox for any active sounds or music.
2. Unplug power from the SFXbox.
3. Disconnect the audio cable from the sound board.
4. Coil the cables neatly.
5. Store the Logitech presenter remote, numeric keypad, and keyboard with the SFXbox.
6. Return all parts to the designated storage location.

Make sure the following items are stored together:

- SFXbox
- Power adapter
- USB audio adapter
- Audio cable
- Stream Deck
- Logitech presenter remote
- Wireless numeric keypad
- Wireless keyboard
- Any needed receivers or dongles

---

## 6. Backup and Alternative Options

The SFXbox has several backup control options.

### Backup 1: Wireless numeric keypad

Use the numeric keypad if the Stream Deck or Logitech remote is not working.

![Wireless numeric keypad](/sfxbox/images/numpad.png)

### Backup 2: Wireless keyboard

Use the wireless keyboard if the other controllers are not working.

![Wireless keyboard](/sfxbox/images/sparekeyboard-connectoronback.png)

### Backup 3: Direct monitor and keyboard access

If the SFXbox needs direct access, connect a monitor using HDMI and use the wireless keyboard.

![Monitor connected to SFXbox](/sfxbox/images/monitor.png)

![HDMI plugged in](/sfxbox/images/hdmi-pluggedin.png)

This should only be needed for troubleshooting or software updates.

---

## 7. Updating the Software with Git Pull

Only do this if Mark asks you to update the SFXbox software.

You will need:

- HDMI monitor connected to the SFXbox
- Wireless keyboard
- The SFXbox powered on

![Monitor showing terminal and git pull](/sfxbox/images/bbplayers-gitpull.png)

### Steps

1. Connect the HDMI monitor if it is not already connected.

   ![HDMI plugged in](/sfxbox/images/hdmi-pluggedin.png)

2. Log in to the SFXbox.

3. Go to the SFXbox folder:

   ```bash
   cd sfxbox
   ```

4. Pull the latest software:

   ```bash
   git pull
   ```

5. Restart the SFXbox service:

   ```bash
   sudo systemctl restart sfxbox-v2
   ```

6. Wait for the ready sound.

7. Test the Stream Deck, presenter remote, and keypad before the show.

---

## 8. Troubleshooting Quick Reference

### No ready sound after startup

Check:

- Is the SFXbox plugged in?
- Is the green power/status light on?
- Is the audio cable connected?
- Is the sound board channel on and turned up?
- Did you wait long enough for startup?

### Ready sound works, but buttons do not play sounds

Try:

1. Press a Stream Deck button.
2. Press the Logitech presenter remote.
3. Press a key on the numeric keypad.
4. Press a mapped key on the wireless keyboard.

If one device works and another does not, use the working device for the show.

### Stream Deck is not working

Check:

- Is the Stream Deck plugged into the SFXbox?
- Are the Stream Deck buttons lit?
- Try the Logitech presenter remote or numeric keypad as a backup.

### Logitech presenter remote is not working

Check:

- Is the Logitech receiver plugged into the SFXbox?
- Is the remote powered on or awake?
- Try pressing a different button.
- Use the Stream Deck or numeric keypad as a backup.

### Numeric keypad is not working

Check:

- Is the keypad powered on?
- Is its receiver plugged in?
- Try the Stream Deck, presenter remote, or wireless keyboard instead.

### No sound from the sound board

Check:

- Audio cable from SFXbox to sound board
- Correct sound board input
- Channel gain/level
- Mute status
- Main output level

If the SFXbox ready sound was heard earlier, the SFXbox itself is probably working and the issue may be sound board routing or levels.

---

## 9. Hardware Inventory

Before storing the system, verify that all parts are present.

- [ ] SFXbox
- [ ] Power adapter
- [ ] USB audio adapter
- [ ] Audio cable
- [ ] Stream Deck
- [ ] Logitech presenter remote
- [ ] Wireless numeric keypad
- [ ] Wireless keyboard
- [ ] USB receivers/dongles
- [ ] HDMI cable, if used
- [ ] Monitor, if used

---

## 10. Notes for Operators

The SFXbox is designed to start automatically when powered on.

For normal show use, you should not need to type commands, open files, or change settings.

The normal process is:

```text
Plug in SFXbox
Wait for ready sound
Test buttons
Run the show
Unplug and store
```

If something goes wrong, use the backup controls first before changing cables or restarting the system.

---

SFXbox User Guide v1.0  
Black Box Players
