# React Native - Preparando o ambiente de desenvolvimento (Windows)

Recursos utilizados: Java JDK, Python, NodeJS, NPM, Android Studio, e React Native.

Tutorial escrito por Guionardo Furlan <guionardo@gmail.com>

## Java JDK

Instalar o JDK SE (Standard Edition, Versão encontrada em 20/05/2018 = Java SE 10.0.1) =>  <http://www.oracle.com/technetwork/java/javase/downloads/index.html>

* Importante: Anote o diretório de instalação do JDK para uso posterior

### Configuração da variável de ambiente JAVA_HOME

## Python

Instalar o Python 2 (Versão em 20/05/2018 = 2.7.15) => <https://www.python.org/downloads/>

* Importante: A versão 3 do Python não é compatível com o React Native.

## NodeJS / NPM

Instalar o NodeJS, (Versão em 20/05/2018 = LTS 8.11.2) => <https://nodejs.org/en/>

Na instalação completa do NodeJS, o NPM (Node Package Management) é instalado automaticamente.

### Teste da instalação NodeJS/NPM

No console:

~~~~
C:\WINDOWS\system32>node -v
v8.11.2

C:\WINDOWS\system32>npm -v
5.6.0
~~~~

## Android Studio

Instalar o Android Studio (Versão em 20/05/2018 = 3.1.2) => <https://developer.android.com/studio/>

* Anote o diretório da instalação do Android SDK.
* Ao término da instalação, desmarque o checkbox que inicia o Android Studio automaticamente.

## React Native

No console, utilize o npm para instalar o React Native CLI

~~~~
C:\WINDOWS\system32>npm install -g react-native-cli
C:\Users\Guionardo\AppData\Roaming\npm\react-native -> C:\Users\Guionardo\AppData\Roaming\npm\node_modules\react-native-cli\index.js
+ react-native-cli@2.0.1
updated 3 packages in 7.62s
~~~~


## Atualizar o SDK Android

Ao abrir o Android Studio, acesse o menu Configure, opção SDK Manager.

![Android Studio SDK Manager](https://github.com/SoftwareColaborativo/Equipe_New-project/blob/master/wiki/setup_android_studio_sdk.png)

É recomendável instalar a última ou as últimas 3 versões da SDK. Para o desenvolvimento final também é importante se ater ao público alvo. Ao usar apenas as últimas versões do Android, o APP pode ficar restrito e não rodar em dispositivos com versões muito antigas, como a 4.4.

![Android Studio SDK Manager](https://github.com/SoftwareColaborativo/Equipe_New-project/blob/master/wiki/setup_android_studio_sdk_2.png)

![Android Studio SDK Manager](https://github.com/SoftwareColaborativo/Equipe_New-project/blob/master/wiki/setup_android_studio_sdk_3.png)

