# Life OS — Android nativo

Aplicativo Android nativo em Kotlin + Jetpack Compose.

## Versões
- `versions/v2.0/`: primeira versão nativa.
- `versions/v2.1/`: revisão visual inicial.
- `versions/v2.2/`: tarefas personalizadas, lembretes e base visual anterior.
- `versions/v2.2.1/`: correção de atualização instantânea das missões e revisão visual compacta.

## v2.2.1
- Atualização reativa da tela ao marcar/desmarcar missões, sem reiniciar a tela ou perder a posição de rolagem.
- Interface mais escura e minimalista, com teal discreto e coral reservado a ações/destaques.
- Dashboard compacto, progresso mais claro e cartões/listas com menos ruído visual.
- Preserva tarefas recorrentes, lembretes Android, conquistas, skills, recompensas, histórico e temporizador.

## Gerar APK
Push em `main` inicia o workflow **Build Life OS APK**. O GitHub Actions recompõe o projeto e publica os artefatos APK e fonte.
