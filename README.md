# ⚔️ AstridQuests 

AstridQuests is a plugin designed exclusively for the AstridCloud server, allowing players to track and complete quests. 🌟 Upon completing quests, players can unlock new levels and check the requirements for the next level.

## ✨ Features

- **📋 Quest Tracking:** Easily check which quests need to be completed.
- **🔓 Level Unlocking:** Unlock levels by completing quests and view the next level's requirements.
- **🎨 Customizable Interface:** Configure how completed, available, and locked levels are displayed.

## ⚙️ Configuration Example

Below is an example configuration for AstridQuests:

```yaml
redeemed:
  type: LIME_STAINED_GLASS_PANE
  name: "Level %level% (REDEEMED)"
  lore:
    - "%description%"

available:
  type: YELLOW_STAINED_GLASS_PANE
  name: "Level %level%"
  lore:
    - "%description%"
    - "Click to redeem"

locked:
  type: YELLOW_STAINED_GLASS_PANE
  name: "Level %level%"
  lore:
    - "%description%"
    - "You can't redeem this yet."

# Level requirement format
level-requirement [%level%]:
  lore: []
  requirement_<value>: "quests_<name>.yml"
```

## 🛑 Important

AstridQuests is specifically developed for the AstridCloud server and is not intended for public distribution or sharing.
