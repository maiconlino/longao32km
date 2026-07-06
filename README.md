# Longão 32km — Semana 14 (11/07/2026)

App de treino para o maior longão do plano: **32km em ritmo de prova**, largada planejada às **03:30 da madrugada**, estimativa de 3h50–4h10.

## Trechos (do plano de treino)
1. **7km em ritmo de conversa** (~7:45/km)
2. **19km a 7:15/km** — ritmo de prova, o alvo principal do treino
3. **6km em ritmo de conversa** (~7:45/km)

Chegada estimada: **~3h58:30** somando os 3 trechos no pace acima.

## Nutrição
- **Gel a cada 30 minutos** (contado a partir do seu START real), alternando sem/com cafeína.
- **Sal a cada 1 hora**, sempre junto com um gel com cafeína.
- **Água a cada 2,5km** — controle próprio (leva pouca água e compra pelo caminho), aparece só como checklist no app, **sem** alerta no relógio.

## Por que o START gera o .ics (corrigindo o bug do app do 15km)
No app da etapa Inverno (15km) os horários dos alertas do `.ics` eram **fixos**, calculados a partir do horário oficial de largada. Quando a largada atrasou, todos os alertas ficaram errados.

Neste app, o arquivo `.ics` **só é gerado depois que você aperta o botão START**, usando o horário real do toque — não um horário fixo. Assim, mesmo que você comece a correr um pouco antes ou depois das 03:30, os alertas de gel/sal batem com o seu início de verdade.

### Como usar
1. Abra o app pouco antes de sair (adicione à Tela de Início pra rodar offline).
2. No momento em que começar a correr, aperte **▶️ START**.
3. Toque em **📅 Baixar alertas atualizados (.ics)** e importe no Calendário do iPhone (abre direto ou pelo app Arquivos).
4. Os alarmes vibram no Apple Watch mesmo durante uma sessão do Runna.
5. Se apertou START por engano, use "reiniciar" no card de alertas.

## Arquivos
`index.html`, `manifest.webmanifest`, `service-worker.js` (offline), `icon.svg`. Sem `.ics` fixo no repositório — ele é sempre gerado no aparelho, na hora.

Publicado via GitHub Pages.
