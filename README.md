
# Criando um App com npx e Expo

Este guia simples ensina como criar um aplicativo React Native usando **npx** com o **Expo**.

## Requisitos
Antes de iniciar, certifique-se de que você possui:

- **Node.js** (versão LTS recomendada)
- **npm** (gerenciador de pacotes que acompanha o Node.js)
- **Git** (sistema de controle de versão)

- [Node.js](https://nodejs.org) (inclui o npm).
- [Git](https://git-scm.com/downloads) (inclui o npm).
- Um emulador Android ou um dispositivo físico para testes.

## Passos

### 1. Criar o Projeto

Instale o expo-cli usando o **npm**:
```
npm install -g expo-cli
```

Abra o terminal e crie o projeto usando **expo**:

```bash
expo init nome-do-projeto
```

Ele dará várias opções de como deseja iniciar o seu projeto, nesse momento escolha a opção **blank**

Depois, entre no diretório do projeto:

```bash
cd nome-do-projeto
```

### 2. Abrir o Projeto no Editor

Se estiver usando o **VSCode**, abra o projeto com o comando:

```bash
code .
```

#### E para rodar o projeto e instalr o modo web (caso seja necessário)
```
npx expo install react-dom react-native-web @expo/metro-runtime
```

Caso utilize outro editor, abra o projeto manualmente.

### 3. Atualizar o npm (Opcional)

Se necessário, atualize o npm com:

```bash
npm install -g npm@10.9.0
```

### 4. Iniciar o Emulador Android

Abra o **Android Studio**

Vá na opção **More Actions** => **Virtual Device Manager** => Icone de **Start** 

Aguarde o emulador inicar, geralmente demora de 2 - 10 minutos (depende da configuração do computador)

Certifique-se de que o emulador Android está rodando no seu computador, ou que o dispositivo físico está conectado.

### 5. Iniciar o Projeto no Expo

Inicie o projeto usando:

```bash
npx expo start
```

No terminal, aparecerão várias opções. Digite `a` para abrir o app no emulador Android (não clique, apenas digite `a` e pressione **Enter**).


## Referências

- [Documentação oficial do Expo](https://docs.expo.dev)

---

#
