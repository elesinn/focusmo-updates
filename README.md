# Focusmo Updates

Sparkle appcast feed for Focusmo app auto-updates.

## Feed URL

```
https://raw.githubusercontent.com/elesinn/focusmo-updates/main/appcast.xml
```

## How to Release a New Version

1. Build and Archive in Xcode
2. Create ZIP: `zip -r focusmo_vX.X.X.zip Focusmo.app`
3. Sign: `sign_update focusmo_vX.X.X.zip`
4. Create GitHub Release, upload ZIP
5. Update appcast.xml with new item
6. Commit and push
