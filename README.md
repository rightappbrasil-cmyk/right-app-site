# Site oficial do RIGHT

Site estático preparado para publicação gratuita no **GitHub Pages**.

## Estrutura

- `index.html` — página inicial
- `style.css` — aparência e responsividade
- `script.js` — menu mobile e ano automático
- `assets/` — logotipo e ícone
- `downloads/right.apk` — arquivo do aplicativo
- `politica-de-privacidade.html`
- `excluir-conta.html`

## 1. Colocar o APK

Gere o APK do Flutter:

```bash
flutter build apk --release
```

O arquivo normalmente será criado em:

```text
build/app/outputs/flutter-apk/app-release.apk
```

Copie esse arquivo para a pasta:

```text
downloads/
```

Renomeie para:

```text
right.apk
```

> O arquivo `right.apk` incluído neste pacote é apenas um marcador vazio. Substitua-o pelo APK verdadeiro.

## 2. Publicar no GitHub

Crie um repositório público, por exemplo:

```text
right-app-site
```

Envie **todos os arquivos e pastas deste pacote para a raiz do repositório**.

## 3. Ativar o GitHub Pages

No repositório:

1. Abra `Settings`.
2. Entre em `Pages`.
3. Em `Build and deployment`, selecione `Deploy from a branch`.
4. Escolha a branch `main`.
5. Escolha a pasta `/ (root)`.
6. Clique em `Save`.

O endereço deverá ficar parecido com:

```text
https://bruno-barradas.github.io/right-app-site/
```

## 4. Atualizações futuras

Sempre que gerar uma versão nova do aplicativo:

1. Substitua `downloads/right.apk`.
2. Faça commit da alteração.
3. Aguarde o GitHub Pages atualizar.

## Atenção

Antes de publicar definitivamente:

- revise a Política de Privacidade;
- informe o e-mail oficial de suporte;
- confirme o fluxo real de exclusão de conta;
- teste o download do APK pelo celular.
