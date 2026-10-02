# WallTeen — app Android

Projeto Android Studio completo do protótipo WallTeen.

## O que já funciona
- Tela inicial responsiva
- Busca e categorias
- Favoritos persistidos no aparelho
- Criador de wallpaper
- Geração de wallpaper em PNG via Canvas
- Salvar na galeria em `Pictures/WallTeen`
- Definir o wallpaper diretamente pelo Android
- Navegação inferior

## Como gerar o APK
1. Instale o Android Studio.
2. Abra esta pasta (`WallTeenAndroid`) no Android Studio.
3. Aguarde a sincronização do Gradle.
4. Conecte um celular Android ou use um emulador.
5. Use `Build > Build APK(s)`.

O APK de debug ficará em `app/build/outputs/apk/debug/app-debug.apk`.

## Observação
Este ambiente não possui o Android SDK/Gradle configurado para compilar o APK aqui. O projeto está preparado para compilação no Android Studio.
