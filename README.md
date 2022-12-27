# ReactNative_WeatherApp
Study ReactNative

환경 구축
Mac일 경우, Homebrew 설치
  -> https://brew.sh/index_ko

node.js 설치
  -> https://nodejs.org/ko/download/


1. Expo CLI 설치
npm install --global expo-cli

혹시 에러가 있다면 아래와 같이 설치하시면 됩니다.
sudo npm install --global expo-cli

https://docs.expo.dev/

Watchman 설치(Mac용)
brew update
brew install watchman


npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'expo-cli@6.0.8',
npm WARN EBADENGINE   required: { node: '>=12 <=16' },
npm WARN EBADENGINE   current: { node: 'v18.12.1', npm: '8.19.2' }
npm WARN EBADENGINE } 에러 나올 경우

nodejs 버전을 12이상 16사이로 다운로드
https://nodejs.org/ko/blog/release/v16.0.0/

--------------------------------------------------------------------------------------------

zsh: command not found: brew 에러 나올 경우

eval $(/opt/homebrew/bin/brew shellenv)

--------------------------------------------------------------------------------------------
command not found: expo 에러 나올 경우

npm bin -g
=========> /Users/계정명/.npm-global/bin 이런식으로 나옴
본인 것 복사하시고

export PATH=${PATH}:/Users/계정명/.npm-global/bin
입력하시면 됩니다.

npm bin -g 후 결과값 복사
export PATH=${PATH}:결과값 붙여넣기
