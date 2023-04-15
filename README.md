# Receita Fácil

O aplicativo de Receita Fácil permite que o usuário visualize diversas receitas de forma detalhada, incluindo vídeo de preparação, lista de ingredientes e modo de preparo. Além disso, é possível favoritar as receitas que mais gostar e também buscar por receitas específicas. Com uma interface intuitiva e fácil de usar, o aplicativo é uma ótima opção para quem deseja aprender novas receitas e explorar diferentes tipos de culinária.

## Interface do App
![Screenshot_20230415_122406_Expo Go](https://user-images.githubusercontent.com/79488603/232234419-76271f51-e2c3-4851-87ca-ce892122eb07.jpg)
![Screenshot_20230415_122429_Expo Go](https://user-images.githubusercontent.com/79488603/232234427-92634acd-67e2-4ca1-b88d-7d0e0e9be2e4.jpg)
![Screenshot_20230415_122555_Expo Go](https://user-images.githubusercontent.com/79488603/232234435-0b2f6097-d2f2-47e1-95b9-c![Screenshot_20230415_122435_Expo Go](https://user-images.githubusercontent.com/79488603/232234468-aced7efa-4002-421e-b0ed-16deb75d6497.jpg)
c17fce25523.jpg)


## Tecnologias utilizadas

- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
-  [Expo](https://docs.expo.dev)
- [React Native](https://reactnative.dev/docs/getting-started)
- [Axios](https://axios-http.com/docs/intro)
- [Json-Serve](https://github.com/typicode/json-server)

## Como executar o projeto

Para estar conseguindo rodas o projeto em sua maquina, as seguintes dependências precisão ser instaladas:

- ####  Instalar o [node js](https://nodejs.org/en)
- #### React Navigation
```
npm install @react-navigation/native
```
- #### SafeAreaContext
```
npx expo install react-native-screens react-native-safe-area-context
```
- #### Native Stack Navigator
```
npm install @react-navigation/native-stack
```
- #### Bottom Tabs Navigator
```
npm install @react-navigation/bottom-tabs
```
- #### Json Server
```
npm install -g json-server
```
- #### Axios
```
npm install axios
```
- #### LinearGradient
```
npx expo install expo-linear-gradient
```
- #### WebView
```
npx expo install react-native-webview
```
- #### Async Storage
```
npx expo install @react-native-async-storage/async-storage
```
- #### Moti
```
npm i moti --legacy-peer-deps
```
- #### Reanimated
```
npx expo install react-native-reanimated
```
- #### Gesture Handler
```
npx expo install react-native-gesture-handler
```

## Executando o projeto
Com as dependências instaladas, vai precisar do seu IPV4, com ele em mão vai dentro da pasta src/services/api.js e na variável baseURL colocar o seu IPV4. Em seguida basta estar rodando o json server com o seguinte comando:
```
json-server --watch -d 180 --host SEUIPV4 db.json
``` 
Em seguida estar rodando o expo.
```
npx expo start
```
