# Checklist — Entrega 02 (Desenho de Software / Modelagem)

Visão geral do que já foi entregue e do que falta em cada subequipe, com base no estado atual dos relatórios em `docs/Base/Relatórios/`. Página de acompanhamento do processo — não faz parte da estrutura fixa exigida pela professora ([1. Modelagem](/Base/1.Modelagem.md)); atualizar conforme os focos forem concluídos.

**Prazo dos artefatos:** quinta-feira, 17/09/2026, conforme [Ata da Reunião Geral 01](/Projeto/Atas/ata-G01-2026-09-11.md).

Legenda: ✅ concluído · 🟡 em andamento · ⬜ não iniciado.

## Visão geral

| Subequipe | FOCO_01 (Estática) | FOCO_02 (Dinâmica) | FOCO_03 (IA Generativa) | Extras |
| -- | -- | -- | -- | -- |
| 🔵 [SubEquipe_01](/Base/Relatórios/1.1.1.SubEquipe_01/1.1.1.SubEquipe_01.md) | 🟡 Em andamento | 🟡 Em andamento | ⬜ Não iniciado | Metodologia, Rastreabilidade e Referências ✅ |
| 🟢 [SubEquipe_02](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.SubEquipe_02.md) | 🟡 Em andamento (0 diagramas inseridos) | 🟡 Em andamento (0 diagramas inseridos) | ⬜ Não iniciado (template) | FOCO_04 Engenharia Reversa ✅ |
| 🟠 [SubEquipe_03](/Base/Relatórios/1.1.3.SubEquipe_03.md) | ⬜ Não iniciado | ⬜ Não iniciado | ⬜ Não iniciado | — |

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
| [FOCO_01 — Modelagem Estática](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.1.Foco01.ModelagemEstatica.md) | 🟡 | Participantes, metodologia, fundamentação teórica (Booch/Rumbaugh/Jacobson; OMG) e matriz de rastreabilidade escritas para Chat e Monetização. | **Nenhum diagrama inserido** — os 4 espaços (Classes e Implantação × Chat e Monetização) só têm o comentário `<!-- Inserir o diagrama ... aqui -->`; Senso Crítico vazio. |
| [FOCO_02 — Modelagem Dinâmica](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.2.Foco02.ModelagemDinamica.md) | 🟡 | Estrutura, metodologia e rastreabilidade dos diagramas de sequência (Recarga, Doação, Saque, Chat) escritas. | **Nenhum diagrama de sequência inserido** (mesmos placeholders `<!-- Inserir ... -->` nos 4 fluxos); Senso Crítico vazio. |
| [FOCO_03 — IA Generativa](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.3.Foco03.IAGenerativa.md) | ⬜ | Página estruturada (Metodologia, Fundamentação, Relatos Individuais, Senso Crítico, Referências). | Ainda é o template padrão, com linha de exemplo "Fulano" — nenhum membro preencheu de fato. |
| [FOCO_04 — Engenharia Reversa](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.4.Foco04.EngenhariaReversa.md) *(extra)* | ✅ | Engenharia reversa do Super Chat de uma segunda plataforma, com evidências (Figuras 26–33) e achados SC01–SC05. | — |
| [Referências](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.5.Referencias.md) | ⬜ | Estrutura da página criada. | Tabela de bibliografia (ABNT) e fontes complementares vazias — só o comentário de instrução. |
| Senso Crítico consolidado (nível subequipe) | ⬜ | — | Trecho da página principal registra "(A preencher com as conclusões globais da entrega de Modelagem)". |
| Versionamentos & Participações (nível subequipe) | ⬜ | Tabela criada com os 4 membros. | Nenhuma linha de contribuição/data/comprobatório preenchida. |

## 🟠 SubEquipe_03 — Autenticação, Telemetria, Moderação

| Item | Status | Já feito | Falta |
| -- | -- | -- | -- |
| [FOCO_01 — Modelagem Estática](/Base/Relatórios/1.1.3.SubEquipe_03.md) | ⬜ | — | Página é só o template original da professora (instruções e linha de exemplo "Fulano"); sem participantes, sem diagrama. |
| FOCO_02 — Modelagem Dinâmica | ⬜ | — | Idem — mesmo arquivo, template não preenchido. |
| FOCO_03 — IA Generativa | ⬜ | — | Idem — mesmo arquivo, template não preenchido. |
| Versionamentos | ⬜ | — | Só a tabela de exemplo; nenhuma contribuição real registrada. |
| Atas da subequipe | ⬜ | Membros presentes na [Reunião Geral 01](/Projeto/Atas/ata-G01-2026-09-11.md). | Nenhuma ata própria da SubEquipe_03 — não existe pasta `Atas_Sg3`, diferente de `Atas_Sg1` e `Atas_Sg2`. |

## Transversais do módulo (Base/)

| Item | Status | Observação |
| -- | -- | -- |
| [1.2 Participações — Modelagem](/Base/1.2.ParticipacoesModelagem.md) | ⬜ | As 3 seções (uma por subequipe) só têm a linha de exemplo ("Fulano"/"Beltrano"/"Ciclano"); nenhuma participação real preenchida. |
| [1.3 Iniciativas Extras](/Base/1.3.IniciativasExtras.md) | ⬜ | Página vazia (só o título). A SubEquipe_02 já tem uma iniciativa extra pronta (FOCO_04 — Engenharia Reversa) que pode ser referenciada aqui. |
| Home ([README.md](/README.md)) | ⬜ | Tabela de alunos com linha placeholder (`xx/xxxxxx`); seções "Sobre" e "Screenshots da Segunda Entrega" vazias. |
