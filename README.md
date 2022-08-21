# tsurekano-api

### What is this?
Data as JSON for images form **tsurekano**

```mermaid
graph LR
    A{Google Colab} -- Download EPs --> B(Extract images using ffmpeg)
    B --> C[(Move images to Google Drive)]
    C --> D{Googlr Apps Script} -- Read all folders --> E(Make JSON File)
```
