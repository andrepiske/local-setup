
Remove:

- `~/Library/Preferences/com.apple.Music.plist`
- `~/Library/Caches/com.apple.Music`
- `~/Library/Application Support/Music`

Disable play/pause handling:

```
launchctl unload -w /System/Library/LaunchAgents/com.apple.rcd.plist
```

