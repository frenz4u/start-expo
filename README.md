# start React Native using expo

## 개발환경 설정
* npm install -g expo-cli
* npm install -g eas-cli

## 생성
* npx direxpo init APP_NAME --npm

(npx create-expo-app APP_NAME)

## 구동
* npm start
* expo start

## 배포
* npx eas build -p android
* npx expo run:android  (run:ios)


( expo build:android )
또는
( npx eas build:configure )