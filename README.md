BFT Gate integration for Home Assistant.

Add this to configuration.yaml
```
cover:
  - platform: bft
    covers:
      bft:
        username: your@username.com
        password: yourpassword
        device: "your device name EXACTLY as you named it in the BFT app"

```
