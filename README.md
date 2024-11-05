# Exotic Survev Client

[WIP, Will Be Out Soon]

[Sample Video Preview](https://github.com/ThatDevExotic/Survev-Client/raw/refs/heads/main/Github%20Assets/GoofyAhhAntiCheat.mp4)

---

## TODO List

### Complete Features
- ✅ Aimbot
- ✅ Spinbot
- ✅ Emote Spam
- ✅ Name Viewer
- ✅ No Ping Cooldown
- ✅ Custom Zoom
- ✅ Draggable Counters (FPS, Health, etc.)
- ✅ Weapon Boarders

### Working on / Planned features
- ❌ Fake 50v50 Mode
- ❌ Access to All Loadout Items
- ❌ User-Friendly UI

# Survev.io Cheats

## UI:

![UI Preview](https://raw.githubusercontent.com/ThatDevExotic/Survev-Client/refs/heads/main/Github%20Assets/ui.png)
![Menu Preview](https://raw.githubusercontent.com/ThatDevExotic/Survev-Client/refs/heads/main/Github%20Assets/menu.png)

## Installation:

For this example, we will use Chrome.

### Steps:

1. **Open Developer Tools**:
   - Press `CTRL + SHIFT + I` to open Chrome Developer Tools, go to the **"Sources"** tab.

   ![Open DevTools](https://raw.githubusercontent.com/ThatDevExotic/Survev-Client/refs/heads/main/Github%20Assets/devtools1.png)

2. **Find the Survev's APP.JS File**:
   - Locate the file named `app-xxxxx.js` in the file system.

   ![Find app.js](https://raw.githubusercontent.com/ThatDevExotic/Survev-Client/refs/heads/main/Github%20Assets/devtools2.png)

3. **Override File Content**:
   - Right-click on the `app-xxxxx.js` file and choose **"Override Content"**.

   ![Override Content](https://raw.githubusercontent.com/ThatDevExotic/Survev-Client/refs/heads/main/Github%20Assets/devtools3.png)

4. **Replace the Code**:
   - Press `CTRL + A` to select all the code inside `app.js`, then replace it with the content from [this client.js file](https://raw.githubusercontent.com/ThatDevExotic/Survev-Client/refs/heads/main/client.js).

5. **Save and Reload**:
   - Press `CTRL + S` to save the changes.
   - Press `CTRL + R` to reload the page. (Note: The client only starts when Developer Tools is open; you can close them after the page loads.)
