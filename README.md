# TODO App (Apache Cordova)
同じ仕様のTODOアプリを様々な技術で実装する実験(Apache Cordova)

## Screenshot
    準備中…

## Features
- 

## Build Setup
```sh
# install dependencies
$ yarn install
$ yarn cordova prepare
```

## Installation
### Android
```sh
$ export PATH=$PATH:$HOME/Library/Android/sdk/tools:$HOME/Library/Android/sdk/platform-tools
$ yarn cordova run android
```

### iOS
```sh
$ yarn cordova run ios
```

## Make
### build
```sh
$ brew install gradle
$ yarn global add npm
$ gitignore code vim windows macos node
$ yarn init
$ yarn add cordova
$ yarn cordova create todoapp org.chimata.u.todoapp.cordova TodoApp
$ rm ./todoapp/package.json
$ mv ./todoapp/* ./todoapp/.* ./
$ rm -r ./todoapp/
$ echo platforms/ >> .gitignore
$ echo plugins/ >> .gitignore
$ yarn cordova platform add android ios browser
$ yarn cordova info
$ jenv add /Library/Java/JavaVirtualMachines/jdk1.8.0_172.jdk/Contents/Home/
$ jenv local 1.8
$ set -Ux JAVA_HOME ( jenv javahome )
$ yarn cordova run
```

### env
```
$ yarn add webpack webpack-command
$ yarn add typescript
$ yarn tsc --init
$ code --install-extension octref.vetur
$ code --install-extension sysoev.language-stylus
$ mkdir ./src
$ mv ./www/js/index.js ./src/app.js
$ touch webpack.config.js
$ echo www/js/app.js >> .gitignore
```

### lint
```
$ code --install-extension eg2.tslint
$ yarn global add tslint
$ touch tslint.json
```

## License
[WTFPL](./LICENSE)

## Author
Uchi (/ɯ̹t͡ɕʲi/)
  - Twitter: [@c18t](https://twitter.com/c18t)
