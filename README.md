# openmtp-testflight
OpenMTP Beta release test repository

```shell
brew install git-lfs
git lfs install   
```

```shell
git lfs track "*.dmg, *.zip"   
git lfs migrate import --include="*.dmg, *.zip" --verbose    
git add .
git commit -am "message"
git push
```
