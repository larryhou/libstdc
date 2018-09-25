# libstdc
Fix for libstdc++.6.0.9.tbd missing issue with Xcode 10

`libstdc++.tbd` and `libstdc++.6.tbd` is an alias of `libstdc++.6.0.9.tbd`, so if the link is broken, then you can fix it by yourself.


```bash
sudo rsync -av libstdc++*.tbd /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk/usr/lib/
```
