# Checklist — Entrega 02 (Desenho de Software / Modelagem)

Visão geral do que já foi entregue e do que falta em cada subequipe, com base no estado atual dos relatórios em `docs/Base/Relatórios/`. Página de acompanhamento do processo — não faz parte da estrutura fixa exigida pela professora ([1. Modelagem](/Base/1.Modelagem.md)); atualizar conforme os focos forem concluídos.

**Prazo dos artefatos:** quinta-feira, 17/09/2026, conforme [Ata da Reunião Geral 01](/Projeto/Atas/ata-G01-2026-09-11.md).

Legenda: ✅ concluído · 🟡 em andamento · ⬜ não iniciado.

## Visão geral

| Subequipe | FOCO_01 (Estática) | FOCO_02 (Dinâmica) | FOCO_03 (IA Generativa) | Extras |
| -- | -- | -- | -- | -- |
| 🔵 [SubEquipe_01](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.SubEquipe_01.md) | ✅ Concluído | ✅ Concluído | ✅ Concluído | Metodologia, Rastreabilidade, Referências, Componentes e Estados ✅ |
| 🟢 [SubEquipe_02](/Base/Relatórios/1.1.2.SubEquipe_02/README.md) | ✅ Concluído (4 diagramas) | ✅ Concluído (8 diagramas) | ✅ Concluído | FOCO_04 Engenharia Reversa ✅ · Atas S2_01 a S2_04 ✅ · Referências ✅ |
| 🟠 [SubEquipe_03](/Base/Relatórios/1.1.3.SubEquipe_03/1.1.3.SubEquipe_03.md) | ✅ Concluído (5 diagramas) | ✅ Concluído (7 diagramas) | ✅ Concluído | Metodologia, Rastreabilidade, Versionamentos, Referências e critérios de aprofundamento ✅ |

## 🔵 SubEquipe_01 — Transmissão ao vivo, UGC, Clipagem

| Item | Status | Já feito | Falta |
| -- | -- | -- | -- |
| [FOCO_01 — Modelagem Estática](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.1.Foco01.ModelagemEstatica.md) | ✅ | Diagrama de classes integrado em quatro componentes: Serviço de domínio (Lucas), UGC/Clipagem (Pedro + Matheus) e Usuários/Canais + Reprodução/Playback (Heitor), com fonte Draw.io, PNG, evidências e decisões DE01–DE10. | — |
| [FOCO_02 — Modelagem Dinâmica](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.2.Foco02.ModelagemDinamica.md) | ✅ | Três diagramas de sequência concluídos: UGC (Lucas), Transmissão ao vivo/A05 (Heitor) e Clipagem/A06 (Pedro + Matheus), com fontes e comprobatórios. | — |
| [FOCO_03 — IA Generativa](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.3.Foco03.IAGenerativa.md) | ✅ | Pontos de vista dos quatro integrantes e registro auditável do uso de Codex e Claude, incluindo acertos, correções e limites. | — |
| [Metodologia](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.4.Metodologia.md) | ✅ | Ritos, ferramentas e fluxo de revisão da subequipe documentados. | — |
| [Rastreabilidade & Elos](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.5.Rastreabilidade.md) | ✅ | Artefatos A01, A04, A05, A06, A07 e A08 ligados às decisões, evidências, fontes e PRs correspondentes. | — |
| [Versionamentos & Participações](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.6.Versionamentos.md) | ✅ | Contribuições dos quatro integrantes registradas por artefato, com datas, PRs e coautorias dos diagramas extras. | — |
| [Referências](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.8.Referencias.md) | ✅ | Bibliografia preenchida. | — |

## 🟢 SubEquipe_02 — Chat ao vivo, Monetização

| Item | Status | Já feito | Falta |
| -- | -- | -- | -- |
| [FOCO_01 — Modelagem Estática](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.1.Foco01.ModelagemEstatica.md) | ✅ | Quatro diagramas concluídos: Diagrama de Classes e Diagrama de Implantação de Monetização (versão final em 4 pacotes conceituais, topologia física em 4 nós com webhook assíncrono e refinamentos A01–A11); Diagrama de Classes e Diagrama de Implantação de Chat (com estereótipos UML). Participantes, metodologia, fundamentação teórica (Booch/Rumbaugh/Jacobson; OMG), matriz de rastreabilidade e senso crítico concluídos. | — |
| [FOCO_02 — Modelagem Dinâmica](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.2.Foco02.ModelagemDinamica.md) | ✅ | Estrutura, metodologia, fundamentação, matriz de rastreabilidade e todos os 8 diagramas de sequência inseridos (Recarga, Doação, Saque, ModuloChat, ConectarEAssinarChat, EnviarMensagemChat, FanoutMensagemChat, ModerarMensagemChat), com validações de auditoria, conciliação Net-15 e senso crítico. | — |
| [FOCO_03 — IA Generativa](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.3.Foco03.IAGenerativa.md) | ✅ | Pontos de vista individuais de todos os quatro integrantes (Davi Severiano, Daniel Lira, Pedro Rodrigues e Mateus Barreto) registrados com lições aprendidas, acertos, alucinações/correções, síntese do uso responsável e comprobatórios. | — |
| [FOCO_04 — Engenharia Reversa](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.4.Extra.EngenhariaReversa.md) *(extra)* | ✅ | Engenharia reversa do Super Chat de uma segunda plataforma (Parte A) e de monetização/repasse ao criador com rotina Net-15 (Parte B), com 20 evidências tarjadas (Figuras 26–45) e catálogo de achados SC01–SC06 e SQ01–SQ16. | — |
| [Atas da Subequipe (S2_01 a S2_04)](/Projeto/Atas/Atas_Sg2/ata-S2-01-2026-09-11.md) | ✅ | Quatro reuniões formais registradas ([Ata S2_01](/Projeto/Atas/Atas_Sg2/ata-S2-01-2026-09-11.md), [Ata S2_02](/Projeto/Atas/Atas_Sg2/ata-S2-02-2026-09-14.md), [Ata S2_03](/Projeto/Atas/Atas_Sg2/ata-S2-03-2026-09-16.md) e [Ata S2_04](/Projeto/Atas/Atas_Sg2/ata-S2-04-2026-09-17.md)) com pautas, deliberações, encaminhamentos 100% concluídos e links de gravação. | — |
| [Referências](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.5.Referencias.md) | ✅ | Bibliografia centralizada em formato ABNT (R01 a R06) e fontes complementares com links, alinhada e citada em todos os relatórios da subequipe. | — |
| Senso Crítico consolidado (nível subequipe) | ✅ | Seção 6 do [README.md](/Base/Relatórios/1.1.2.SubEquipe_02/README.md) preenchida com as conclusões globais da entrega (interdependência estático-dinâmica, ceticismo ativo contra alucinações de IA e lastro empírico por engenharia reversa). | — |
| Versionamentos & Participações (nível subequipe) | ✅ | Tabela 7 do [README.md](/Base/Relatórios/1.1.2.SubEquipe_02/README.md) integralmente preenchida com detalhamento de contribuições, datas e comprobatórios (commits e atas) para Davi, Daniel, Mateus e Pedro, com histórico de versões v1.0 a v1.7. | — |

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
| [1.2 Participações — Modelagem](/Base/1.2.ParticipacoesModelagem.md) | ✅ | Participações de todas as subequipes (01, 02 e 03) preenchidas com significância e comprobatórios claros com links. |
| [1.3 Iniciativas Extras](/Base/1.3.IniciativasExtras.md) | ✅ | Iniciativas da SubEquipe 01 (Componentes e Estados), SubEquipe 02 (Engenharia Reversa Complementar, Atas e Referências) e SubEquipe 03 (Aprofundamento) consolidadas com comprobatórios. |
| Home ([README.md](/README.md)) | ✅ | Apresentação do projeto, alunos, escopo, três screenshots representativos, instruções de visualização e atalhos para os artefatos. |
