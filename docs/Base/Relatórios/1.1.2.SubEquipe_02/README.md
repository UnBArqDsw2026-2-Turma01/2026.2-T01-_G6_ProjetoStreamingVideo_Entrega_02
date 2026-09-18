# 1.1.2. SubEquipe_02 — Relatório (Entrega 2 · Modelagem)

> Este relatório cobre os **quatro focos** da Entrega 2. Nenhum tópico deve ser omitido.

## 1. Composição da Subequipe

| Membro | GitHub | Papel na subequipe |
| -- | -- | -- |
| Davi Severiano Freitas | [@Davi-UnB](https://github.com/Davi-UnB) | Líder |
| Daniel de Oliveira Lira | [@Daniellira540](https://github.com/Daniellira540) | dev |
| Pedro Henrique Freire Rodrigues | [@Pedro-Henrique3](https://github.com/Pedro-Henrique3) | dev |
| Mateus Rodrigues Barreto | [@Mateus0xC](https://github.com/Mateus0xC) | dev |

## 2. Escopo Trabalhado

| Item | Definição | Justificativa |
| -- | -- | -- |
| Módulo de Chat | Diagrama de Classes, Diagrama de Implantação e Diagrama de Sequência | Pedro Henrique Freire Rodrigues e Daniel de Oliveira Lira ficaram responsáveis pela abstração estrutural e dinâmica do Chat, conforme [Ata S2_02](/Projeto/Atas/Atas_Sg2/ata-S2-02-2026-09-14.md). |
| Módulo de Monetização | Diagrama de Classes, Diagrama de Implantação e Diagrama de Sequência | Davi Severiano Freitas e Mateus Rodrigues Barreto ficaram responsáveis pelos diagramas estáticos e dinâmicos da aquisição de moedas virtuais e doações, conforme [Ata S2_02](/Projeto/Atas/Atas_Sg2/ata-S2-02-2026-09-14.md). |
| Engenharia Reversa (Extra) | Documentação de apoio | Iniciativa extra da subequipe para dar maior embasamento arquitetural aos diagramas elaborados. |

## 3. Índice do Relatório

| Foco | Página | Status |
| -- | -- | -- |
| FOCO_01 | [Modelagem Estática](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.1.Foco01.ModelagemEstatica.md) | 🟡 Em andamento |
| FOCO_02 | [Modelagem Dinâmica](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.2.Foco02.ModelagemDinamica.md) | 🟢 Concluído |
| FOCO_03 | [IA Generativa](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.3.Foco03.IAGenerativa.md) | 🟢 Concluído |
| Extra | [Engenharia Reversa](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.4.Extra.EngenhariaReversa.md) | 🟢 Concluído |
| — | [Referências](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.5.Referencias.md) | 🟢 Concluído |

## 4. Metodologia da Subequipe

O trabalho da SubEquipe_02 foi pautado na colaboração por módulos funcionais, conforme definido na [Ata S2_02](/Projeto/Atas/Atas_Sg2/ata-S2-02-2026-09-14.md). Diferente da divisão inicial, optou-se pela especialização total em domínios: Chat e Monetização. O desenvolvimento iterativo foi conduzido com o apoio de ferramentas como o `sequencediagram.org` e o `PlantUML` para validação sintática da lógica, além da verificação cruzada através de diagramas dinâmicos para aprimorar os diagramas estáticos (como registrado nas atas [Ata S2_03](/Projeto/Atas/Atas_Sg2/ata-S2-03-2026-09-16.md) e [Ata S2_04](/Projeto/Atas/Atas_Sg2/ata-S2-04-2026-09-17.md)), sendo o trabalho final consolidado na ferramenta visual Miro.

## 5. Rastreabilidade & Elos com Outros Artefatos (visão consolidada)

| Artefato desta subequipe | Origem / insumo | Elo com | Observação |
| -- | -- | -- | -- |
| **Modelagem Estática** | Módulos de Monetização e Chat | [Modelagem Dinâmica](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.2.Foco02.ModelagemDinamica.md) | Define a estrutura de classes e relações que sustenta as regras de negócio. |
| **Modelagem Dinâmica** | Fluxos Mapeados (Entrega 1) | [Modelagem Estática](/Base/Relatórios/1.1.2.SubEquipe_02/1.1.2.1.Foco01.ModelagemEstatica.md) | Detalha a troca de mensagens no tempo para interações de chat e pagamentos. |
| **Engenharia Reversa** | Plataforma de referência | Focos 01 e 02 | Mapeia componentes e APIs como base empírica da modelagem de software. |

## 6. Senso Crítico (visão consolidada)

O senso crítico detalhado de cada foco está registrado nas páginas dos respectivos artefatos. Consolidando a vivência da SubEquipe_02 ao longo da Entrega 2:
- **Interdependência Estático-Dinâmica**: A modelagem dinâmica por meio dos diagramas de sequência revelou-se indispensável para auditar e validar o modelo estático de classes. Atributos essenciais (como chaves de idempotência em transações financeiras e carimbos de auditoria em mensagens quarentenadas) só emergiram com clareza ao desenhar a troca temporal de mensagens.
- **Validação Empírica contra Suposições de IA**: A adoção de uma postura de ceticismo ativo assegurou que nenhuma alucinação de LLMs (como dependências síncronas inviáveis ou generalizações excessivas) fosse incorporada sem confirmação empírica e revisão técnica humana.
- **Engenharia Reversa como Lastro de Domínio**: Aprofundar a investigação das regras contratuais e fluxos de repasse (ciclo Net-15) e do Super Chat garantiu que os diagramas refletissem restrições reais de sistemas de streaming em escala de produção.

## 7. Versionamentos & Participações

| Membro | Contribuição | Data | Comprobatório (commit/PR) |
| -- | -- | -- | -- |
| Davi Severiano Freitas | Estrutura base dos relatórios; FOCO_01 (senso crítico, classes de Monetização); FOCO_02 (sequências de Monetização); FOCO_03 (ponto de vista e fechamento); Extra ER Parte B (habilitação/repasse e evidências) | 16–18/09/2026 | [`d7da100`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/d7da100270875690e6d1f6ecdfa2a4bcd91989ac) · [`43c0d2c`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/43c0d2cbff90a04f82238a16860ad3c4babed664) · [`b454a32`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/b454a32e3dc73c773d49b63ed0f0a36a6a03fce4) · [`1332f9e`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/1332f9ebddf1b81a6f78d0ff4288c52bc17fb8df) · [`b9a2f9b`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/b9a2f9b14d7a03ce36f8d6d1b55642cb0d758a12) · [`a5df84a`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/a5df84af92bda9f78a6ad8c6a0aede70a6640df1) · [`801143c`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/801143c10c12b233d39e1bbc44331b2849355040) · [`190c467`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/190c467752ae9e23add0a0e1a48a3d2fe737007c) · [`f2909f0`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/f2909f0f886b1322814b8f384ce87fe17d059737) |
| Daniel de Oliveira Lira | FOCO_01/02: assets e diagramas estáticos; sequências de Chat (`FanoutMensagemChat`, `ModerarMensagemChat`); correção de caminhos | 16–17/09/2026 | [`969f60a`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/969f60a758bacacc018791f2245c8860b721c1e6) · [`7c72da5`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/7c72da543850e38c01d3ac56323f0e76984a0547) · [`703ebaf`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/703ebafb655014bd4e7ae519ebea9aed4bdfc0a2) |
| Pedro Henrique Freire Rodrigues | FOCO_02: documentação e sequências de Chat (`ModuloChat`, `ConectarEAssinarChat`, `EnviarMensagemChat`); FOCO_03: ponto de vista, rastreabilidade e síntese da subequipe | 16–18/09/2026 | [Ata S2_02](/Projeto/Atas/Atas_Sg2/ata-S2-02-2026-09-14.md) · Histórico FOCO_02 v1.2 · [`9e410a4`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/9e410a4f8ab820a49a29aad141c6b70e2861cfa9) · [`7176fbb`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/7176fbb3a50e64e30b90a9a488180e9489942d18) · [`793162a`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/793162a496e72d609ef9ec4f7218ab75d7d35d5b) |
| Mateus Rodrigues Barreto | Estrutura inicial FOCO_01/02; Extra ER Parte A (Super Chat / SC01–SC06); FOCO_03: ponto de vista individual | 16–18/09/2026 | [`fb23b62`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/fb23b6260239d5c40726aafc298f466e7a3c7783) · [`7d31399`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/7d31399db78b0711fe621eac17966668ff787e8a) · [`dedff67`](https://github.com/UnBArqDsw2026-2-Turma01/2026.2-T01-_G6_ProjetoStreamingVideo_Entrega_02/commit/dedff67128a452755601e4da9987cf9f34950154) |

---

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| -- | -- | -- | -- | -- |
| 1.0 | 16/09/2026 | Criação e estruturação do relatório principal da SubEquipe_02 | Davi Severiano Freitas | |
| 1.1 | 18/09/2026 | Atualização do status dos focos concluídos (Modelagem Dinâmica, Engenharia Reversa e Referências) e correção dos links internos para rotas absolutas do Docsify | Davi Severiano Freitas | Daniel de Oliveira Lira, Mateus Rodrigues Barreto, Pedro Henrique Freire Rodrigues |
| 1.2 | 18/09/2026 | Preenchimento de Versionamentos & Participações com commits da Entrega 2 | Pedro Henrique Freire Rodrigues | |
| 1.3 | 18/09/2026 | Atualização do status do FOCO_03 (IA Generativa) para concluído após inclusão de todos os relatos individuais | Davi Severiano Freitas | Daniel de Oliveira Lira, Mateus Rodrigues Barreto, Pedro Henrique Freire Rodrigues |
| 1.4 | 18/09/2026 | Preenchimento do senso crítico consolidado da SubEquipe_02 na entrega de modelagem | Davi Severiano Freitas | Daniel de Oliveira Lira, Mateus Rodrigues Barreto, Pedro Henrique Freire Rodrigues |