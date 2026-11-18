# Prompts de IA usados no projeto

A IA (Claude Code) foi usada como copiloto para aprender e revisar, como permite o briefing da GS. Conforme o briefing da GS, os prompts ficam registrados aqui e o grupo sabe explicar cada linha.

| # | Prompt (resumo) | O que foi feito |
| --- | --- | --- |
| 1 | "Descubra de onde vem o mapa do aplicativo." | Identificado: OpenStreetMap exibido com Leaflet dentro de um WebView (`app/src/components/mapaHtml.ts`). |
| 2 | "Qual seria o mapa mais bonito?" | Comparação de provedores (Mapbox, MapTiler, Stadia, CARTO). O grupo decidiu manter o OpenStreetMap, que é gratuito e sem chave. |
| 3 | "Quando o teclado abre ele tampa tudo; a tela precisa subir e mostrar o campo acima do teclado." | Criado o hook `app/src/components/useTeclado.ts`, usado em "Nova ocorrência" e nos comentários. |
| 4 | "A build do APK falhou." | Lido o log do GitHub Actions: erro de tipo do `ref` do `ScrollView`. Corrigido e validado com `tsc --noEmit`. |
| 5 | "Leia o PDF da GS e monte o plano de dublagem do vídeo de Mobile Development & IOT." | Levantados os requisitos da disciplina e escrito o roteiro do vídeo de até 3 minutos. |
| 6 | "Confira o checklist antes de entregar." | Conferido o README e o repositório; atualizados os links e criado este arquivo. |
