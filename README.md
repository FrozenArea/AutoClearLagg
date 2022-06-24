# General
The plugin you need to keep your server lagg free!

# Features
- [x] Enable/Disable Mobs & Items clearing
- [x] NEW: Exempt entities from clearing
- [x] Configurable Timer
- [x] Editabe Messages

# Config
```yaml
---
# AutoClearLagg (ACL) Config

# Seconds between each clear lagg
seconds: 300

# Entities to clear
clear:
  items: true
  mobs: true
  exempt: # Array of entities not to clear
    - Zombie
    - Pig

messages:
  time-left: "§cEntities will clear in {SECONDS} seconds"
  entities-cleared: "§cCleared a total of {COUNT} entities"

# Countdown times
times: [60, 30, 15, 10, 5, 4, 3, 2, 1]
...
```

# Contact
[![Discord](https://img.shields.io/discord/986553214889517088?label=discord&color=7289DA&logo=discord)](https://discord.gg/j2X83ujT6c)\
**You can contact me directly via Discord `NhanAZ#9115`**
