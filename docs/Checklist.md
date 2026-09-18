# Checklist — Entrega 02 (Desenho de Software / Modelagem)

Visão geral do que já foi entregue e do que falta em cada subequipe, com base no estado atual dos relatórios em `docs/Base/Relatórios/`. Página de acompanhamento do processo — não faz parte da estrutura fixa exigida pela professora ([1. Modelagem](/Base/1.Modelagem.md)); atualizar conforme os focos forem concluídos.

**Prazo dos artefatos:** quinta-feira, 17/09/2026, conforme [Ata da Reunião Geral 01](/Projeto/Atas/ata-G01-2026-09-11.md).

Legenda: ✅ concluído · 🟡 em andamento · ⬜ não iniciado.

## Visão geral

| Subequipe | FOCO_01 (Estática) | FOCO_02 (Dinâmica) | FOCO_03 (IA Generativa) | Extras |
| -- | -- | -- | -- | -- |
| 🔵 [SubEquipe_01](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.SubEquipe_01.md) | 🟡 Em andamento | 🟡 Em andamento | ⬜ Não iniciado | Metodologia, Rastreabilidade e Referências ✅ |
| 🟢 [SubEquipe_02](/Base/Relatórios/1.1.2.SubEquipe_02/README.md) | 🟡 Em andamento | ✅ Concluído (8 diagramas) | 🟡 Em andamento | FOCO_04 Engenharia Reversa ✅ · Referências ✅ |
| 🟠 [SubEquipe_03](/Base/Relatórios/1.1.3.SubEquipe_03/1.1.3.SubEquipe_03.md) | ✅ Concluído (5 diagramas) | ✅ Concluído (7 diagramas) | ✅ Concluído | Metodologia, Rastreabilidade, Versionamentos, Referências e critérios de aprofundamento ✅ |

## 🔵 SubEquipe_01 — Transmissão ao vivo, UGC, Clipagem

| Item | Status | Já feito | Falta |
| -- | -- | -- | -- |
| [FOCO_01 — Modelagem Estática](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.1.Foco01.ModelagemEstatica.md) | 🟡 | Diagrama de classes com os 4 pacotes desenhados; componente *Serviço de domínio* (Lucas) e pacote *Conteúdo gerado pelo usuário / Clipagem* (Matheus + Pedro Druck, [aditivo v2](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.1.2.Foco01.ConteudoGeradoUsuario.md)) preenchidos, com 13 evidências e decisões DE01–DE10. | Atributos/operações dos pacotes **Usuário / Canais** (A01, Matheus) e **Reprodução / Playback** (A03, Heitor) — tabela de estado ainda marca os dois como `⬜ a preencher`. |
| [FOCO_02 — Modelagem Dinâmica](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.2.Foco02.ModelagemDinamica.md) | 🟡 | Diagrama de sequência *Iniciar transmissão ao vivo (UGC)* (Lucas) completo, com evidências e decisões DM01–DM06. | Diagramas de sequência dos temas **Transmissão ao vivo** (Heitor) e **Clipagem** (Pedro Druck + Matheus, em dupla) — atribuídos na [Ata S1_01](/Projeto/Atas/Atas_Sg1/ata-S1-01-2026-09-15.md), ainda "em andamento". |
| [FOCO_03 — IA Generativa](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.3.Foco03.IAGenerativa.md) | ⬜ | Página estruturada (tabela de participantes + registro de uso de IA). | Nenhum dos 4 membros preencheu lições aprendidas / uso de IA generativa; tabela de registro de uso de IA vazia. |
| [Metodologia](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.4.Metodologia.md) | ✅ | Ritos, ferramentas e fluxo de revisão da subequipe documentados. | — |
| [Rastreabilidade & Elos](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.5.Rastreabilidade.md) | 🟡 | Elos A01–A04 e decisões D01–D04 registrados. | Artefatos A05 (sequência Transmissão) e A06 (sequência Clipagem) marcados `(pendente)`. |
| [Versionamentos & Participações](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.6.Versionamentos.md) | 🟡 | Lucas com 2 PRs registrados; contribuição de Matheus/Pedro Druck registrada (tabela separada, revisão UGC). | Linhas de Matheus e Pedro Druck na tabela principal de Contribuições vazias; Heitor sem nenhuma contribuição registrada. |
| [Referências](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.8.Referencias.md) | ✅ | Bibliografia preenchida. | — |

## 🟢 SubEquipe_02 — Chat ao vivo, Monetização

| Item | Status | Já feito | Falta |
| -- | -- | -- | -- |
| [FOCO_01 — Modelagem Estática](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.1.Foco01.ModelagemEstatica.md) | 🟡 | Participantes, metodologia, fundamentação teórica (Booch/Rumbaugh/Jacobson; OMG) e matriz de rastreabilidade. Diagramas de classes de Chat e Monetização inseridos, diagrama de implantação de Chat inserido. | Diagrama de implantação de Monetização e fechamento do Senso Crítico. |
| [FOCO_02 — Modelagem Dinâmica](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.2.Foco02.ModelagemDinamica.md) | ✅ | Estrutura, metodologia, fundamentação, matriz de rastreabilidade e todos os 8 diagramas de sequência inseridos (Recarga, Doação, Saque, ModuloChat, ConectarEAssinarChat, EnviarMensagemChat, FanoutMensagemChat, ModerarMensagemChat). | — |
| [FOCO_03 — IA Generativa](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.3.Foco03.IAGenerativa.md) | 🟡 | Página estruturada (Metodologia, Fundamentação, Relatos Individuais, Senso Crítico, Referências). | Preenchimento dos relatos individuais e reflexões de cada integrante da subequipe. |
| [FOCO_04 — Engenharia Reversa](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.4.Extra.EngenhariaReversa.md) *(extra)* | ✅ | Engenharia reversa do Super Chat de uma segunda plataforma e de monetização/repasse ao criador, com evidências (Figuras 26–45) e achados SC01–SC06 e SQ01–SQ16. | — |
| [Referências](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.5.Referencias.md) | ✅ | Bibliografia preenchida em formato ABNT (R01 a R06) e fontes complementares com links. | — |
| Senso Crítico consolidado (nível subequipe) | ⬜ | — | Trecho da página principal registra "(A preencher com as conclusões globais da entrega de Modelagem)". |
| Versionamentos & Participações (nível subequipe) | ⬜ | Tabela criada com os 4 membros. | Nenhuma linha de contribuição/data/comprobatório preenchida. |

## 🟠 SubEquipe_03 — Autenticação, Telemetria, Moderação

| Item | Status | Já feito | Falta |
| -- | -- | -- | -- |
| [FOCO_01 — Modelagem Estática](/Base/Relatórios/1.1.3.SubEquipe_03/1.1.3.1.Foco01.ModelagemEstatica.md) | ✅ | Cinco diagramas de classes em PlantUML, SVG e PNG: arquitetura integrada, visão geral do domínio, autenticação e controle de acesso, moderação e telemetria. O foco documenta recursos UML, decisões `DE01`–`DE10`, limitações e senso crítico. | — |
| [FOCO_02 — Modelagem Dinâmica](/Base/Relatórios/1.1.3.SubEquipe_03/1.1.3.2.Foco02.ModelagemDinamica.md) | ✅ | Sete diagramas comportamentais (`DYN-01` a `DYN-07`): três de sequência, um de estados e três de atividades. Os fluxos cobrem moderação, segurança de conteúdo, telemetria, audiência e qualidade, com requisitos `RD-M01`–`RD-M04` e `RD-T01`–`RD-T03`, decisões `DD01`–`DD09`, cenários alternativos e visualização com zoom. | — |
| [FOCO_03 — IA Generativa](/Base/Relatórios/1.1.3.SubEquipe_03/1.1.3.3.Foco03.IAGenerativa.md) | ✅ | Pontos de vista aprofundados de Eduardo, Hugo e Philipe; lições aprendidas; exemplos concretos de acertos, alucinações e correções; registro das interações; síntese crítica e diretrizes de uso responsável. | — |
| [Metodologia](/Base/Relatórios/1.1.3.SubEquipe_03/1.1.3.4.Metodologia.md) | ✅ | Acordos de trabalho, divisão por domínio, *Definition of Done*, revisão cruzada, ferramentas, reunião própria e checklist formal de qualidade documentados. | — |
| [Rastreabilidade & Elos](/Base/Relatórios/1.1.3.SubEquipe_03/1.1.3.5.Rastreabilidade.md) | ✅ | Matrizes `RST-01`–`RST-05` e `RST-D01`–`RST-D07`, catálogo de 30 evidências (`EV-01`–`EV-30`) e matriz cruzada entre fontes, classes, requisitos e fluxos. | — |
| [Versionamentos & Participações](/Base/Relatórios/1.1.3.SubEquipe_03/1.1.3.6.Versionamentos.md) | ✅ | Contribuições de Eduardo, Hugo e Philipe detalhadas por foco, com datas, artefatos comprobatórios, autoria, revisão e históricos incrementais. | — |
| [Referências](/Base/Relatórios/1.1.3.SubEquipe_03/1.1.3.8.Referencias.md) | ✅ | Referências em formato ABNT organizadas por foco, fontes normativas e técnicas, insumos empíricos da Entrega 01 e matriz que relaciona 44 classes UML às respectivas fontes. | — |
| [Ata da subequipe](/Projeto/Atas/Atas_Sg3/ata-S3-01-2026-09-15.md) | ✅ | Reunião presencial `S3_01` registrada com participantes, pauta, decisões `D01`–`D05`, divisão dos artefatos e encaminhamentos `A01`–`A07`; também há vínculo com a [Reunião Geral 01](/Projeto/Atas/ata-G01-2026-09-11.md). | — |
| [Critérios de aprofundamento](/Base/1.3.IniciativasExtras.md#subequipe_03) | ✅ | Fundamentação de artefatos e decisões; rastros metodológicos do trabalho em equipe; emprego combinado de diagramas de classes, sequência, estados e atividades; pontos de vista fundamentados, claros e críticos. | — |

## Transversais do módulo (Base/)

| Item | Status | Observação |
| -- | -- | -- |
| [1.2 Participações — Modelagem](/Base/1.2.ParticipacoesModelagem.md) | 🟡 | Participações das SubEquipes 01 e 03 preenchidas com significância e comprobatórios; falta consolidar a SubEquipe 02. |
| [1.3 Iniciativas Extras](/Base/1.3.IniciativasExtras.md) | 🟡 | Iniciativas da SubEquipe 01 e critérios de aprofundamento da SubEquipe 03 registrados com comprobatórios; falta incorporar a iniciativa de engenharia reversa da SubEquipe 02. |
| Home ([README.md](/README.md)) | ⬜ | Tabela de alunos com linha placeholder (`xx/xxxxxx`); seções "Sobre" e "Screenshots da Segunda Entrega" vazias. |
