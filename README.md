# Netrunner (APK)

Projeto Android que embute o jogo (`app/src/main/assets/index.html`) num WebView em tela cheia, horizontal.
Botão voltar = pausa. Os saves ficam no armazenamento do app.

## Gerar o APK — opção A: GitHub (sem instalar nada)
1. Crie um repositório no GitHub e envie o conteúdo desta pasta (inclusive `.github`).
2. Aba **Actions** > **Build APK** > aguarde ficar verde.
3. Abra a execução e baixe o artefato **Netrunner-apk** (`app-debug.apk`).
4. No celular: permita "instalar apps desconhecidos" e abra o arquivo.

## Opção B: Android Studio
Abra esta pasta > **Build > Build Bundle(s)/APK(s) > Build APK(s)**.
O arquivo sai em `app/build/outputs/apk/debug/app-debug.apk`.

Para atualizar o jogo, troque `app/src/main/assets/index.html` e gere de novo.
