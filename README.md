# DeskPal avatars

VRM avatars that DeskPal can download from its **Browse VRM avatars** window.
DeskPal reads `avatars.json` from this repo and downloads the `.vrm` files listed in it.

## Add an avatar
1. Put the `.vrm` file in this folder (lowercase name, no spaces is safest).
2. Add an entry to `avatars.json`:
   ```json
   { "name": "Shown name", "author": "Creator", "license": "CC BY", "file": "my-avatar.vrm" }
   ```
3. Commit and push. DeskPal picks it up next time someone presses **Refresh**.

Only add avatars whose license allows redistribution, and keep the credit.

## Credits
- **Chibi Among Us** by miaru3d, licensed CC BY (from the model's own VRM metadata).
