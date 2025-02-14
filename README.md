# Crow Call

![GitHub repo size](https://img.shields.io/github/repo-size/iuricode/README-template?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/iuricode/README-template?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/iuricode/README-template?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/iuricode/README-template?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/iuricode/README-template?style=for-the-badge)

<img src="assets/imagem.PNG" alt="Crow Call">

> Projeto inspirado no Zoom, onde é possivel criar videochamadas, agendar e gravar.

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

- Você instalou a versão mais recente de `Node`
- Você tem uma máquina `<Windows / Linux / Mac>`.

## ☕ Usando Crow Call

Para usar Crow Call, siga estas etapas:

1. Instale as dependencias:
```

npm install

```
2. Crie um arquivo .env:
```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```
3. Crie uma conta no Clerk:
   
<img src="assets/clerk.png" alt="Tela criar conta">

4. Copie as duas keys e cole em:

<img src="assets/clerkkeys.png" alt="Keys">

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
```
5. Crie uma conta no Stream:

<img src="assets/stream.png" alt="Tela criar conta">

6.Copie as duas keys e cole em:

<img src="assets/streamkeys.png" alt="Keys">

```env
NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

## 📝 Licença

Esse projeto está sob licença. Veja o arquivo [LICENÇA](LICENSE.md) para mais detalhes.
