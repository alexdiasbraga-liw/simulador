# Simulado Transpetro - APK

## Gerar o APK (uma vez, ~15 min)
1. Crie uma conta gratuita em github.com (se ainda não tiver).
2. Crie um repositório novo (pode ser privado) chamado `simulador-transpetro`.
3. Envie TODO o conteúdo desta pasta para o repositório
   (botão "Add file > Upload files"; arraste os arquivos e pastas, incluindo a pasta oculta `.github`).
4. Abra a aba **Actions**. O workflow "Build APK" roda sozinho (leva ~5-8 min).
   Se não rodar, clique em "Build APK" > "Run workflow".
5. Quando ficar verde, abra a execução e baixe o arquivo **simulador-transpetro-apk** (zip) em "Artifacts".
6. Extraia o zip: dentro está o `app-debug.apk`.

## Instalar no celular
1. Passe o `app-debug.apk` para o celular (Drive, WhatsApp, cabo...).
2. Abra o arquivo e permita "instalar apps de fontes desconhecidas" quando o Android pedir.
3. Pronto: o app "Simulado Transpetro" aparece na tela inicial.

## Observações
- Funciona 100% offline; histórico e tentativas ficam salvos no próprio app.
- Desinstalar o app apaga o histórico.
- O PDF do relatório abre a tela de compartilhar do Android (salvar no Drive, enviar, etc.).
- Para atualizar o simulador, troque `www/index.html` no GitHub: o APK é gerado de novo.
