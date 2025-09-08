# VibyTweeks Minecraft Server – Join Instructions

Welcome to the **VibyTweeks Server** 🎉  
Follow this guide carefully to get connected.

---

## 1. Install Minecraft Forge (Client)

Our server runs **Minecraft 1.20.1** with **Forge 47.4.0**.  
You must install the matching Forge client.

👉 Download Forge Installer (Recommended):  
- [Forge 1.20.1 – 47.4.0](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.20.1.html)

**How to install Forge:**
1. Run the downloaded `.jar` file.  
2. Select **Install Client**.  
3. Launch the Minecraft Launcher, go to **Installations**, and select the new **Forge 1.20.1** profile.

---

## 2. Install the Modpack

⚠️ **Important: You must install the mods provided in this repository.**

1. Download the contents of this repo "VibyTweeks_pack.zip (or the provided release `.zip`).  
2. **Unzip/Extract the folder** — do not place the `.zip` file directly into your `mods` folder.  
   - After extracting, you should see a collection of `.jar` files (the mods).  
3. Locate your Minecraft `mods` folder:  
   - **Windows:** `%appdata%/.minecraft/mods`  
   - **Linux/Mac:** `~/.minecraft/mods`  
4. Copy all the `.jar` files from the unzipped folder into your `mods` folder.  
   - ✅ Only `.jar` files should be inside `mods/`  
   - 🚫 Do **not** leave them inside another subfolder.  
5. Ensure you are launching with the **Forge 1.20.1** profile.

---

### Example Directory (Windows)

```text
C:\Users\<YourName>\AppData\Roaming\.minecraft\mods\

├── curios-forge-5.13.0+1.20.1.jar
├── elytraslot-forge-6.4.4+1.20.1.jar
├── farmersdelight-forge-1.20.1-2.9.jar
├── ironchest-1.20.1-14.4.4.jar
├── jei-1.20.1-forge-15.20.0.111.jar
├── ... (other mod .jars)


## 3. Join the Server

1. Open Minecraft (Forge 1.20.1 profile).  
2. Click **Multiplayer** → **Add Server**.  
3. Enter the server address (ask the admin for the IP).  
4. Name it whatever you like (e.g., *VibyTweeks*).  
5. Click **Join Server**.

---

## 4. Recommended Client-Side Mods

These mods are not required, but improve the experience.  
You can safely install them on your client — the server doesn’t need them.

- [**Jade**](https://www.curseforge.com/minecraft/mc-mods/jade) – shows tooltips with block/item info  
- [**AppleSkin**](https://www.curseforge.com/minecraft/mc-mods/appleskin) – adds hunger & saturation overlay  
- [**Xaero’s Minimap**](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap) – minimap with waypoints  
- [**Xaero’s World Map**](https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map) – fullscreen world map  
- [**Controlling**](https://www.curseforge.com/minecraft/mc-mods/controlling) – better keybind management  
- [**Mouse Tweaks**](https://www.curseforge.com/minecraft/mc-mods/mouse-tweaks) – improved inventory controls  

---

## 5. Troubleshooting

### ❌ "Missing mods" or "mod mismatch" error
- Make sure your client has **all the mods from this repo** in the `mods` folder.  
- Versions must match exactly with the server.

### ❌ Game crashes on startup
- Double-check you installed **Forge 47.4.0 for 1.20.1**.  
- Remove any extra mods not listed here (especially other versions of Forge mods).  

### ❌ "Client attempted to load class ... for invalid dist DEDICATED_SERVER"
- You accidentally put a **client-only mod** (like Jade or Xaero) on the server.  
- Remove it from the server’s `mods/` folder — keep it client-side only.

### ❌ Still having issues?
- Delete your `mods/` folder and reinstall the modpack from this repo.  
- If Forge itself is corrupted, reinstall Forge and try again.

---

✅ You’re ready to play!  
See you on the **VibyTweeks Server** 🚀
