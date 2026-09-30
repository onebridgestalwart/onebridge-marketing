# Onebridge Stalwart · Site

Versão 2 · 2026-09-30 · Artefato 1 de plan/marketing-plan.md v3

## Para que serve

O site é fundação, não canal. As pessoas chegam porque um parceiro nos mencionou, um fundador escreveu, uma busca as trouxe ou um lembrete as fez voltar. Para elas, o site confirma a um escritório o que a mensagem do fundador disse, dá a uma família ou empresa uma superfície crível antes da conversa, e transforma tráfego pago em conversas agendadas, com um filtro no meio.

Mantemos o site atual como base. O enquadramento é famílias versus empresas, mais fácil de entender do que proteção versus expansão. A home é terreno comum. Os parceiros têm a própria face.

## O que muda

| Página | Mudança |
|---|---|
| Home | Duas portas, "Para famílias" e "Para empresas", no lugar dos cards de solução. Selos do hero revisados. Seção da plataforma sem link |
| `/familias` (antes `/protecao-patrimonial`, com redirecionamento) | Guiada por benefícios: jurisdição estável, fora do alcance de bloqueios, sucessão por instrumento, pronto para crescer em dólar, tudo declarado. Provas, "Escopo e preço", fluxo na página |
| `/empresas` (antes `/expansao-internacional`) | Linguagem de mercado e estabilidade no lugar de "sonho americano" e "rentabilidade". Imigração como componente. Provas, "Escopo e preço", fluxo na página |
| `/parceiros` | Reconstruída na ordem em que vencemos: vídeo, o catálogo com a Holding nos EUA como primeira venda, os dois modelos, plataforma com link, profundidade, três etapas, one-pager atrás de um formulário curto, fluxo na página |
| `/plataforma` | Nova. Só para parceiros, com link apenas em `/parceiros`. Telas reais. White-label a caminho, sem data |
| `/quem-somos` | Uma linha por fundador, com a credencial da OAB redigida por Walter. Marca anterior sem nome |
| `/contato` | Roteador por público, carregando o fluxo da face escolhida. Endereço completo |

"Agendar consulta" dá lugar a um CTA por público. Cada face resolve na própria página; nenhuma envia o visitante para `/contato`.

## Perguntas e agendamento

Um componente, três configurações. Três a cinco perguntas, uma decisão de adequação e, para quem se encaixa, a agenda da equipe comercial no Google Calendar na hora. Quem não se encaixa recebe uma resposta cortês e assíncrona; pedidos bem definidos vão ao catálogo da plataforma. Cada resposta e agendamento entra no CRM com público, adequação e origem.

| Caminho | Perguntas | CTA |
|---|---|---|
| Parceiro | Tipo de escritório, porte, perfil dos clientes, se já perguntam sobre os EUA, disposição de assumir o cliente | Conversa com um fundador |
| Família | Faixa de patrimônio, ativos no Brasil versus fora, situação familiar, gatilho | Conversa confidencial |
| Empresa | Faturamento, atividade atual nos EUA, prazo, quem toca a operação | Diagnóstico da operação |

## Medição

Google Tag Manager, GA4, Google Ads e Meta Pixel com Conversions API pelo servidor da plataforma. O banner de consentimento bloqueia toda tag não essencial, conforme a LGPD. A conversão principal é o agendamento, medido por uma URL de confirmação por público; também medimos o fluxo, o download do one-pager e o progresso do vídeo, sinais que tiram firmas do remarketing. Nenhum dado pessoal vai a plataforma de anúncios. Cada envio guarda origem, mídia e campanha, para que a regra do dinheiro seja lida por canal dentro da plataforma.

## Conformidade com plataformas de anúncios

O Google Ads e a Meta analisam as páginas de destino. O selo "60% menos impostos" sai e o contador fabricado vira número real ou ilustração rotulada. "Rentabilidade" e "LLC é blindagem" são reescritos. Imigração aparece como componente, nunca como oferta principal. "Escopo e preço" entra nas duas páginas de serviço: preço fixo por serviço cotado por escrito após o diagnóstico, compliance anual recorrente, CPAs por hora. Endereço físico em `/contato` e no rodapé.

## Ordem de trabalho

Primeiro a face de parceiros, porque condiciona a abordagem. Depois a frente direta, porque condiciona a busca. Por fim navegação e `/quem-somos`. Está pronto quando um escritório que recebeu a mensagem de um fundador encontra a mesma mensagem em `/parceiros`, cada face agenda na hora e grava no CRM com origem, as conversões disparam com consentimento respeitado e Walter revisou credencial e respostas tributárias. Depois deixamos o site em paz.

Pendências: endereço em Orlando, agenda da equipe comercial, vídeo e one-pager, redação da credencial, telas da plataforma. O texto de cada página é redigido em `content/`.
