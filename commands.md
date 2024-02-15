# React Native Commands

## Create React native app
```bash
npx react-native init TestProject
npx react-native init TestProject --version 0.72
```
## clean gradle file
```bash
cd android
./gradlew clean
```
## clean gradle file
```bash
react-native run-android
react-native run-ios
```
## build test-and release
```bash
cd android
./gradlew Asswmblerelease
./gradlew BundleRelease
```
## Pod commands
```bash
cd ios
pod install
pod deintegrate
pod init
pod install --repo-update
```
## command to build emulator
```bash
yarn start
yarn ios
yarn android

#find devices
abd devices
```
## clean watchman cache
```bash
watchman watch-del-all
```
## License

[MIT](https://choosealicense.com/licenses/mit/)
