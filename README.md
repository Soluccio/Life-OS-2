# Life OS — Android nativo

Aplicativo Android nativo em Kotlin + Jetpack Compose, sem WebView.

## Linha de versões
- `versions/v2.0/`: snapshot histórico da primeira versão nativa.
- `versions/v2.1/`: snapshot da primeira revisão visual.
- `versions/v2.2/`: versão atual com dashboard compacto, nova identidade, tarefas personalizadas e lembretes sonoros.

## Life OS v2.2
Paleta `#002A32` / `#ED254E`, interface híbrida e compacta, tipografia mais legível, ícone de compasso redesenhado, estados de sobrevivência, progressão visual e animações discretas. Inclui calendário, histórico, conquistas, habilidades, recompensas, timer, tarefas recorrentes e lembretes do Android.

## Gerar APK
Push em `main` ou `v2.2-staging` inicia **Build Life OS APK**. O workflow reconstrói o fonte Kotlin a partir de `versions/v2.2/payload-b64/`, compila o APK e publica o artifact `life-os-v2.2-debug-apk`.

## Dados e alarmes
O progresso fica no armazenamento privado do aplicativo. Os lembretes são notificações Android com som de alarme; dependem da permissão de notificações, do som/canal de notificações do dispositivo e das permissões de alarmes exatos. Sem alarmes exatos, o Android pode adiar um lembrete.
