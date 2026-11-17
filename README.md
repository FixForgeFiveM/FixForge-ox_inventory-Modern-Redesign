# FixForge | ox_inventory Modern Redesign

<p align="center">
  <strong>FIXFORGE DEVELOPMENT</strong><br>
  <em>Modern Red & Black Inventory Interface</em>
</p>

A modern visual redesign of the **ox_inventory** interface, crafted by **FixForge Development**. This build gives your server a distinctive red-and-black appearance with glass-inspired panels, refined inventory slots, clean typography, and polished interaction states.

**FixForge project:** ox_inventory Modern Redesign  
**Package type:** UI replacement  
**Design direction:** Modern / Red & Black  
**Maintained by:** FixForge Development

---
<img width="1455" height="667" alt="Screenshot 2026-11-17 144640" src="https://github.com/user-attachments/assets/a4e97051-3097-4979-9da9-aaec779fa644" />

<img width="604" height="131" alt="image" src="https://github.com/user-attachments/assets/ddafc33c-a8af-461a-a207-cdc12c1ec0c5" />


## ✦ Features

- **FixForge red & black visual identity** across the inventory interface
- Glass-inspired panels with translucent surfaces and background blur
- Refined inventory slots with rounded corners and subtle depth
- Modern red gradient action buttons
- Redesigned item tooltips and context menus
- Cleaner weight and durability indicators
- Updated hotbar and item notifications
- Modern Inter and system-style typography
- Smooth hover, focus, and click feedback
- Responsive sizing for different screen resolutions
- Original inventory JavaScript and interactions preserved

## 📦 Package contents

This FixForge package includes the built web interface and this installation guide.

```text
FixForge-ox_inventory-modern-redesign/
├── README.md
└── build/
    ├── index.html
    ├── LICENSE
    └── assets/
        ├── index.js
        └── index.css
```

> **Important:** This is a visual redesign only. It replaces the built web UI assets; it does not include the full ox_inventory resource and does not add or modify inventory gameplay features, Lua scripts, SQL files, or item definitions.

## Requirements

- A working installation of **ox_inventory**
- Access to your FiveM server's resources directory
- Permission to replace files inside the ox_inventory resource

## 🛠️ Installation

### 1. Back up your current interface

1. Stop your FiveM server, or make sure the `ox_inventory` resource is stopped before replacing its UI files.
2. Open your server's resources directory.
3. Locate your `ox_inventory` resource.
4. Open `ox_inventory/web/`.
5. Rename the existing `build` folder to `build_backup` or copy it somewhere safe.

Example resource structure:

```text
resources/
└── [ox]/
    └── ox_inventory/
        └── web/
            └── build/
```

Your resource folder may be in a different category. The important destination is `ox_inventory/web/`.

### 2. Install the FixForge build

1. Download and extract the FixForge ZIP package.
2. Open the extracted package.
3. Copy the included `build` folder.
4. Paste it into `ox_inventory/web/`.
5. Confirm that the existing `build` folder and its files are replaced.

Your final paths must look exactly like this:

```text
ox_inventory/web/build/index.html
ox_inventory/web/build/assets/index.js
ox_inventory/web/build/assets/index.css
```

**Avoid nesting the folders.** The incorrect path would be `ox_inventory/web/build/build/index.html`.

### 3. Restart ox_inventory

Start your server or restart the resource from the server console:

```text
restart ox_inventory
```

No additional resource needs to be added to `server.cfg`. Keep your existing ox_inventory installation and dependencies.

### 4. Verify the redesign

Join your server and open your inventory. The FixForge modern red-and-black interface should now be displayed.

If the previous design is still visible:

- Close and reopen the inventory.
- Restart your FiveM client.
- Clear the FiveM client cache if the old interface continues to appear.

## 🔄 Updating or reverting

### Updating

When FixForge releases a newer build, back up your current `web/build` folder and repeat the installation steps with the new package.

### Reverting to the previous interface

1. Stop or restart `ox_inventory`.
2. Remove the currently installed `ox_inventory/web/build` folder.
3. Rename your backup folder back to `build`.
4. Restart the resource.

## Troubleshooting

| Problem | What to check |
|---|---|
| The old design still appears | Confirm the new files are in `ox_inventory/web/build/`, restart the resource, and restart FiveM. |
| The inventory UI does not load | Check that `index.html`, `assets/index.js`, and `assets/index.css` exist at the expected paths. Restore your backup if needed. |
| Files were installed into `build/build/` | Move the inner `build` folder into `ox_inventory/web/`. There should only be one `build` directory. |
| Inventory errors appear | Restore your backup and inspect the F8 client console and server console for errors. |

## Compatibility & important notes

- Designed as a visual replacement for the built ox_inventory web interface.
- This package contains only the `build` assets and this FixForge README.
- It does not include the complete ox_inventory resource.
- It does not require changes to `server.cfg`, Lua configuration, SQL, or item definitions.
- Keep your original ox_inventory resource and dependencies installed.
- The appearance may vary slightly depending on screen resolution and the ox_inventory version/build in use.
- Always keep a backup before replacing production files.

## Credits & licensing

**UI redesign and package documentation:** FixForge Development  
**Original inventory resource:** [overextended/ox_inventory](https://github.com/overextended/ox_inventory)

This is an unofficial visual modification. **FixForge Development is not affiliated with, endorsed by, or representing the original ox_inventory developers.**

The original ox_inventory license file is included in this package. Please review and comply with the applicable license and notices before using or redistributing the original or modified assets.

---

<p align="center">
  <strong>FIXFORGE DEVELOPMENT</strong><br>
  <em>Built to make your server stand out.</em>
</p>
