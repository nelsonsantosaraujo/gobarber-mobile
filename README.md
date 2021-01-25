<h1 align="center">
  <img alt="Logo" src="https://ik.imagekit.io/t58nj4hrrhv/logo_o0SeXCgx_Q.svg" alt="GoBarber Hairdcuts and Shaves">
</h1>

<h1 align="center">
    GoBarber - React Native App
</h1>
<p align="center">Aplicação para cadastro e gerenciamento de agendamentos para barbearias</p>


<p align="center">
 <a href="#notebook-sobre-o-projeto">Sobre o Projeto</a> •
 <a href="#🚀-tecnologias">Tecnologias</a> •
 <a href="#💻-configurações-necessárias">Configurações necessárias</a> •
 <a href="#📝-licença">Licença</a> •
 <a href="#autor">Autor</a>
</p>

<h4 align="center">
	🚧  GoBarber 🚀 Projeto para estudo finalizado 🚧
</h4>

## 📓 Sobre o projeto

GoBarber é um projeto para barbearias realizarem a gestão dos agendamentos de seus prestadores de serviço e seus clientes.

Foi desenvolvido durante o ***Bootcamp 14*** da ***[Rocketseat](https://rocketseat.com.br)***

Esta aplicação tem como objetivo fornece uma interface para dispositivos mobile em forma de aplicativo para cadastro de usuários e a criação de agendamentos com fornecedores de serviço.

Para utilização desta aplicação é necessário a configuração da API:

- ***API:*** [GoBarber API REST](https://github.com/nelsonsantosaraujo/gobarber-backend)

Para cadastro de fornecedores utilizar o cliente web

- ***Cliente web:*** [GoBarber Web](https://github.com/nelsonsantosaraujo/gobarber-web)

---

## 🚀 Tecnologias

Abaixo as tecnologias utilizadas para construção do App

- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [UnForm](https://unform.dev/)
- [Yup](https://github.com/jquense/yup)
- [Axios](https://github.com/axios/axios)

---

## 💻 Configurações necessárias

### **Requisitos**

- Necessário [API](https://github.com/nelsonsantosaraujo/gobarber-backend) estar em execução
- Instalar Android Studio e realizar as configurações do [ambiente de desenvolvimento](https://reactnative.dev/docs/environment-setup)
- Dispositivo físico ou emulador para execução do aplicativo

### **Clone do projeto**

```bash
# Execute o comando git clone para realizar o clone do repositório
$ git clone https://github.com/nelsonsantosaraujo/gobarber-mobile.git

# Entre na pasta do repositório clonado
$ cd gobarber-mobile
```

### **Iniciando o projeto**

```bash
# Execute yarn para instalar as dependências
$ yarn

# Verifique se o ip de sua API está configurada corretamente em 'src/services/api.ts'

# Inicialize o emulador ou conecte o dispositivo físico
# verificando dispositivos disponíveis
adb devices

# Para iniciar a aplicação no Android execute
$ yarn android

# Para iniciar a aplicação no IOS execute
$ yarn ios

# Caso o projeto não execute ou fique travado na splash screen
# Execute os seguintes comandos:

# 1- Em uma janela de terminal execute (mantenha está janela aberta)
# Ela é responsável por controlar o Bundle do projeto
$ npx react-native start

# 2- Em uma segunda janela de terminal execute
# Para Android
$ npx react-native run-android
# Para IOS
$ npx react-native run-ios

```

---

## 📝 Licença

Distribuído sob a licença MIT. Veja [LICENSE](LICENSE) para mais informações.

---

### Autor


Feito por Nelson Araújo 👋🏽 Entre em contato!

[![Linkedin Badge](https://img.shields.io/badge/-Nelson-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/tgmarinho/)](https://www.linkedin.com/in/nelsonsantosaraujo/)
[![Gmail Badge](https://img.shields.io/badge/-nelsonsantosaraujo@hotmail.com-red?style=flat-square&link=mailto:nelsonsantosaraujo@hotmail.com)](mailto:nelsonsantosaraujo@hotmail.com)
