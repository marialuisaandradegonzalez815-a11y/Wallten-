# WallTeen — versão final de preparação para Google Play

- applicationId: com.wallteen.app
- nome: WallTeen
- targetSdk/compileSdk: 36
- Premium sem anúncios
- Google Play Billing 9.1.0
- produto esperado: wallteen_premium_monthly
- ícone adaptativo
- splash screen
- versão 1.0.0 / versionCode 1

Abra no Android Studio, sincronize o Gradle e gere:
Build > Generate Signed Bundle / APK > Android App Bundle.

Antes de publicar:
1. Crie o produto de assinatura no Play Console com ID wallteen_premium_monthly.
2. Configure preço e países.
3. Faça testes internos.
4. Gere o AAB assinado.
5. Complete as declarações de conteúdo, segurança de dados e página da loja.
6. Teste em Android 16 e em versões anteriores suportadas.

Observação: a cobrança real exige configuração do produto no Play Console e validação adequada da compra; este projeto prepara a dependência e a interface Premium.
