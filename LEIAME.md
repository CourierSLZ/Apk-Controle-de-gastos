# Controle de Gastos (Android 15 / targetSdk 35)

App Android nativo (Kotlin) que embute a checklist em um WebView.
Funciona offline, sem permissoes.

## Opcao A - Android Studio (mais simples)
1. Instale o Android Studio (https://developer.android.com/studio).
2. File > Open > selecione esta pasta e aguarde o sync do Gradle.
3. Build > Build APK(s). O arquivo sai em app/build/outputs/apk/debug/app-debug.apk
4. Envie o APK ao celular e instale (permita "instalar apps desconhecidos").
   Ou conecte o celular com depuracao USB e clique em Run.

## Opcao B - sem instalar nada (GitHub Actions)
1. Crie um repositorio no GitHub e suba o conteudo desta pasta.
2. Aba Actions > "Build APK" > aguarde ~3 min.
3. Baixe o artefato "todo-sh-apk" (contem o app-debug.apk).
