# ecoleta
O Ecoleta é um projeto criado para ajudar pessoas a encontrarem pontos de coleta de uma forma mais eficiente.

## Next Level Week 
Rocketseat (https://rocketseat.com.br/) 

## Tecnologias

1. [Node.js](https://nodejs.org/en/)
2. [ReactJS](https://reactjs.org)
3. [React Native](https://facebook.github.io/react-native/)
4. [TypeScript](https://www.typescriptlang.org/)
5. [Expo](https://expo.io/)
6. [Knex](http://knexjs.org/)
7. [SQLite](https://www.sqlite.org/index.html)

## Projeto e Dependências

>Configurações Gerais

- Instalar a extensão: JSON Viewer no Chrome.
- Instalar o Insomnia: https://insomnia.rest/download/
- Necessário instalar o gerenciador de pacotes, baixar e instalar o Chocolatey: https://chocolatey.org/
- Para instlar o Chocolatey é preciso executar o Power Shell como Administrador (Windows)

- No Power Shell:
  - Executar o comando: Get-ExecutionPolicy. 
  - Se retornar Restricted, então executar Set-ExecutionPolicy AllSigned ou Set-ExecutionPolicy Bypass -Scope Process.
  - Instalar o NodeJS
  - Para utilizar a versão mais estável do node deve-se executar o comando: choco install nodejs-lts
  - Para verificar as versões: node -v e npm -v

>./server - API REST usando TypeScript, Express e banco de dados SQLite

- npm install express
- npm install @types/express -D
- npm install ts-node -D
- npm install typescript -D
- npm install ts-node-dev -D 
- npm install knexs
- npm install sqlite3
- npm install @types/cors -D
- npm knex:migrate
- npm knex:seeds
- npm install multer 
- npm install @types/multer -D
- npm install celebrate
- npm install @types/hapi__joi -D
- npm run dev (Rodar o Projeto)

>./web - Interface web em RectJS e TypeScript

- npm install react-icons 
- npm install react-router-dom 
- npm install @types/react-router-dom -D
- npm install leaflet react-leaflet
- npm install @types/react-leaflet -D
- npm install axios
- npm install --save react-dropzone
- npm start (Rodar o Projeto)

>./mobile - Interface mobile em ReactNative, TypeScript e Expo 

- npm install -g expo-cli
- expo start
- expo install expo-font @expo-google-fonts/ubuntu @expo-google-fonts/roboto
- npm install @react-navigation/native
- expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
- npm install @react-navigation/stack
- expo install react-native-maps
- expo install expo-constants
- expo install react-native-svg
- npm install axios
- expo install expo-location
- expo install expo-mail-composer
