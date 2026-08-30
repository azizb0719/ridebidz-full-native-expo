# ridebidz-full-native-expo

Contains the Expo-managed app and a GitHub Actions workflow that uses EAS to produce a Play-ready AAB and attach it to a GitHub Release.

How to run the build locally:
1. npm install -g eas-cli
2. eas login
3. eas build --platform android --profile production

How to use GitHub Actions:
1. Add the repository secret EXPO_TOKEN (see below).
2. (Optional) Add keystore secrets if you want to supply your own signing key.
3. Go to Actions → choose "Build and publish" workflow → Run workflow (or push to main).
