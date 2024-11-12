# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## 개발환경 설정
* npm install -g expo-cli
* npm install -g eas-cli

## 생성
* npx create-expo-app APP_NAME : 체계적 구조
* npx direxpo init APP_NAME --npm : 간단한 구조

## 구동
: WEB 에서 개발 현황 확인 가능
   ```bash
    npm (run) start
    npx expo start
   ```
In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

## 빌드
* npx expo run:android  (run:ios) : 실행 및 배포를 위한 명령어지만, 폴더 구조도 만들어 준다

## 배포
* npx eas build -p android (expo build:android 하면, eas를 사용 제안) : https://expo.dev/ 통해 확인 및 배포
( npx eas build:configure )

## 개발

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
