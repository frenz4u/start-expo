# start React Native using expo


## 개발환경 설정
* npm install -g expo-cli
* npm install -g eas-cli

## 생성
* npx create-expo-app APP_NAME : 체계적 구조
* npx direxpo init APP_NAME --npm : 간단한 구조

## 구동
: WEB 에서 개발 현황 확인 가능
* npm start
* expo start

## 빌드
* npx expo run:android  (run:ios) : 실행 및 배포를 위한 명령어지만, 폴더 구조도 만들어 준다

## 배포
* npx eas build -p android (expo build:android 하면, eas를 사용하라고 나온다) : https://expo.dev/ 통해 확인 및 배포
( npx eas build:configure )
