---
theme: gaia
_class: lead
paginate: true
backgroundColor: #484d6d
color: #fff
---

# Desenvolvimento multiplataforma com javascript


---

![bg left:40% 80%](https://enieber.com.br/image/logo-primary.png)

# Sobre mim

 - Desenvolvedor fullstack
 - Amante de programação funcional
 - Usuario de muito javascript
 - Musico nas horas vagas

https://enieber.com.br

---

# Caminho

![bg right:40% 80%](https://images.unsplash.com/photo-1626626063417-4a96f5422b1e?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=386&q=80)

 - Multiplataforma
 - Web
 - React Native
 - Code
 - Expo

--- 

# Multiplataforma

Diz-se multiplataforma um programa ou sistema que pode ser executado em mais do que uma plataforma. (Wikipedia)

Exemplo:

- Browser

---

## Web é multiplataforma

- Gnu/Linux
- Windows
- MacOS
- Android
- iOS
- TV

---

## Problemas da web?

Alguns problemas de desenvolvimento web vai alem do uso de telas responsivas

- performace
- segurança
- offline

--- 

## Performace

A performace de aplicativos web vai depender do browser.

- App
- Browser
- OS

---

## Segurança

Como um webapp está rodando dentro de um browser, vai depender das APIs dos Browsers, além de ter mais um local para ser explorado vulnerabilidades.

- Atualização de Browser
- APIs do Browser
- Mais uma superficie de ataque ( browser)

---

## Offline

No Browser tem um numero limitado de dados que podem ser salvos offline com uma segurança necessaria para alguns casos

- tamanho de cache
- algumas limitações de tipos de cache

--- 

# Ta, mas como fazer multiplataforma alem de web?

![bg right:40% 80%](https://www.veetrack.com/assets/images/blogs/top-8-web-browsers-for-2020-and-beyond.jpg)

- Chrome
- Firefox
- Safari
- Edge

---

# Aplicativos Nativos

Para resolver esses problemas podemos usar aplicativos nativos para cada plataforma.

- Android
- iOS
- Web
- Desktop
- TV

---

# Como fazer?

- Java/Kotlin
- Objective-C/Swift
- C++
- .Net
- Python
- JS

---

# Por que javascript?

- Uma linguagem que nasceu para rodar no browser (alem do WebAssembly)
- Não é muito dificil de aprender
- Roda em multiplataforma
- Tem um ecossistema grande apesar de caotico.

---

# Algumas Ferramentas em JS

- Ionic
- Native Framework
- React Native

---

# React Native

- usa componentização
- compartilha codigo entre plataformas
- compila nativamente para cada plataforma

---
# Aonde roda React Native

- Web (react-native-web)
- TV
- Android
- iOS
- Desktop


---

## Para usar React Native

- conhecer JS
- conhecer a plataforma que quer desenvolver
- focar na experiencia de usuario
- conhecer react

---

##  Exemplo de aplicativos usando React Native

- facebook
- instagram
- discord
- skype
- pinterest

---

## Primeiro App


```tsx
import React, {Component} from 'react';
import {Platform, StyleSheet, Text, View} from 'react-native';

export default class App extends Component {
  render() {
    return (
      <View>
	<Text>Ola mundo!</Text>
      </View>
    );
 }
}
```

---

# Alguns Cuidados

- Separar logica visual de regra de negocio
- Toda compilação vai ser nativa
- O envio de um app para a plataforma usada depende da plataforma (Apple Store, Play Store, Windows Store)


---


# Expo

Uma ferramenta que abstrai a parte nativa para (Android e iOS).

https://expo.dev/

---

# Agradecimento

- Latinoware 2014
- Professores do IFMT - Barra do graças
- Comunidades de desenvolvimento (React Native Drops, DebXP)

---

# Perguntas?

![bg right:40% 80%](https://i1.wp.com/www.petrede.com.br/wp-content/uploads/2011/03/cachorro-pergunta-petrede.jpg?fit=432%2C360)

https://twitter.com/enieber/
