# Life OS — Android nativo

Aplicativo Android nativo em Kotlin + Jetpack Compose, sem WebView.

## Linha de versões
- `versions/v2.0/`: snapshot da primeira versão nativa.
- `versions/v2.1/`: snapshot da atualização visual e funcional atual.
- `versions/v2/`: projeto Android completo da linha v2.

## Release ativa: v2.1
Interface híbrida e compacta, paleta `#002A32` / `#ED254E`, ícones vetoriais Material, barras do sistema em modo compatível, XP consistente, modos de sobrevivência que recolhem a rotina normal e temporizador que preserva o tempo pausado.

Inclui painel, ritual de chegada, missões semanais, histórico, calendário, conquistas, skills, recompensas personalizadas e sessões de foco.

## Gerar APK
Push na branch `main` inicia o workflow **Build Life OS APK**. Também é possível iniciar manualmente em **Actions → Build Life OS APK → Run workflow**. O APK fica no artifact `life-os-v2.1-debug-apk`.

O workflow reutiliza uma chave de assinatura de debug em cache para manter a mesma assinatura entre builds futuros. O APK inicial v2.0 foi assinado por um runner temporário; a primeira atualização pode exigir desinstalar a versão anterior. Depois da instalação da v2.1, as próximas atualizações usarão a chave estável do workflow.

## Dados
O progresso fica no armazenamento privado do aplicativo no próprio aparelho. Não há sincronização em nuvem.
