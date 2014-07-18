XcodeUserData
=============

Xcode的UserData目录，这样就可以到处同步了

目录位置：~/Library/Developer/XCode/UserData/

## Useage
当换了机器，Xcode需要重新配置时

```
cd ~/Library/Developer/XCode/UserData/
git init
git add CodeSnippets/ FontAndColorThemes/ KeyBindings/
git commit -am "local commit"
git remote add origin $你的git地址
git pull origin master
git push origin master
```