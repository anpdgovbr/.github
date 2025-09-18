# 🏛️ Agência Nacional de Proteção de Dados (ANPD) 🇧🇷

**Bem-vindo ao GitHub oficial da Agência Nacional de Proteção de Dados (ANPD).**

Este espaço é dedicado à transparência, inovação e colaboração. Aqui você encontrará o código-fonte de nossas soluções, documentações técnicas e projetos de P&D que impulsionam a proteção de dados no Brasil.

---

## 🚀 Nossos Princípios

- **Código Aberto:** Nossas soluções são desenvolvidas de forma aberta para promover o reuso e a colaboração.
- **Transparência:** Disponibilizamos documentação e processos para que a sociedade possa acompanhar nosso trabalho.
- **Inovação:** Buscamos constantemente novas tecnologias para fortalecer a cultura de proteção de dados.
- **Interoperabilidade:** Criamos sistemas que se comunicam de forma eficiente com outras plataformas do ecossistema gov.br.

---

## 📌 Projetos em Destaque

Explore nossos principais repositórios próprios:
| Repositório | Descrição | Status |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------ | -------------------------------------------------------------------------- |
| 📊 [`backlog-dim`](https://github.com/anpdgovbr/backlog-dim) | Aplicação CRUD para gestão de demandas administrativas e backlog | ![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow) |
| 🚀 [`controladores-api`](https://github.com/anpdgovbr/controladores-api) | Microsserviço responsável pela gestão de Controladores e Encarregados | ![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow) |
| 🔐 [`rbac`](https://github.com/anpdgovbr/rbac) | Monorepo de pacotes RBAC de sistema de permissões e autorizações | ![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow) |
| 📦 [`shared-types`](https://github.com/anpdgovbr/shared-types) | Biblioteca TypeScript com tipos e contratos compartilhados | ![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow) |
| ✨ [`shared-ui`](https://github.com/anpdgovbr/shared-ui) | Biblioteca de componentes React, desenvolvida com MUI e Storybook | ![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow) |
| 🐳 [`docker-infra-pg`](https://github.com/anpdgovbr/docker-infra-pg) | Ambiente Docker para um PostgreSQL 15 puro e pgAdmin | ![Status](https://img.shields.io/badge/Status-Ativo-green) |
| 📰 [`Ro-dou`](https://github.com/anpdgovbr/Ro-dou) | Gerador de DAGs no Apache Airflow para facilitar clipping de DOU | ![Status](https://img.shields.io/badge/Status-Ativo-green) |
| � [`gerador-assinatura`](https://github.com/anpdgovbr/gerador-assinatura) | Web part SPFx para gerar assinaturas de email institucionais padronizadas | ![Status](https://img.shields.io/badge/Status-Ativo-green) |
| �🗄️ [`docker-infra-mssql`](https://github.com/anpdgovbr/docker-infra-mssql) | Ambiente Docker para um MS SQL Server 22 puro | ![Status](https://img.shields.io/badge/Status-Ativo-green) |
| 📚 [`doc_manuais`](https://github.com/anpdgovbr/doc_manuais) | Manuais da ANPD - documentação oficial e institucional | ![Status](https://img.shields.io/badge/Status-Ativo-green) |

Outros repositórios próprios em planejamento ou privados:

- `controladores-api-quarkus` (versão alternativa da API de controladores em Quarkus)
- `controladores-api-springboot` (versão da API de controladores implementada em Spring Boot)
- `gh-project-template` (estrutura base de projetos usando GitHub)

Forks de projetos relevantes:

- `sei` (ramificação do projeto SEI)
- `mod-sei-pen` (módulo de integração ao Tramita.GOV.BR)
- `mod-wssei` (módulo de webservice SEI)

> **Nota sobre visibilidade:**
>
> - Repositórios **públicos** promovem transparência e colaboração.
> - Repositórios **privados** são projetos em planejamento, com dados sensíveis ou não prontos para acesso público.
> - Repositórios **forks** não são listados, exceto o [`Ro-dou`](https://github.com/anpdgovbr/Ro-dou), por relevância técnica.
> - Tudo o que for legalmente possível será feito usando princípios de **código aberto**.

---

## 🛡️ Políticas de Segurança e Privacidade

### 🔐 **Segurança de Código**

- Todos os repositórios seguem nossa [Política de Segurança](SECURITY.md)
- **Dependabot** ativo para atualizações automáticas de dependências
- **Revisão obrigatória** de código para mudanças críticas
- **Scan automático** de vulnerabilidades

### 📋 **Padrões de Contribuição**

- Templates padronizados para [Issues e Pull Requests](.github/)
- [Código de Conduta](CODE_OF_CONDUCT.md) baseado no Contributor Covenant
- [Guia de Contribuição](CONTRIBUTING.md) detalhado
- **Processo estruturado** de revisão e aprovação

### 🏛️ **Conformidade Institucional**

- ✅ Todos os projetos aderem às diretrizes da **LGPD**
- ✅ Código desenvolvido seguindo **padrões gov.br**
- ✅ **Documentação técnica** disponível publicamente
- ✅ **Licenças abertas** compatíveis com uso governamental

---

## 🤝 Como Contribuir

Agradecemos o interesse em colaborar com a ANPD! Nossa comunidade de código aberto está em constante crescimento.

### 📋 **Guias de Contribuição Disponíveis**

- 📚 [**Guia Completo de Contribuição**](CONTRIBUTING.md) - Processo detalhado para colaborar
- 📜 [**Código de Conduta**](CODE_OF_CONDUCT.md) - Diretrizes para interação respeitosa
- 🔐 [**Política de Segurança**](SECURITY.md) - Como reportar vulnerabilidades de forma responsável

### 🚀 **Formas de Contribuir**

#### 🐛 **Reporte Bugs**

- Use nossos [templates de issue](https://github.com/anpdgovbr/.github/tree/main/.github/ISSUE_TEMPLATE) padronizados
- Inclua informações detalhadas sobre o problema
- Considere o contexto da LGPD/ANPD em seus relatos

#### ✨ **Sugira Funcionalidades**

- Abra issues com o template de feature request
- Descreva como a funcionalidade beneficiaria a proteção de dados
- Considere a interoperabilidade com outros sistemas gov.br

#### 🔧 **Contribua com Código**

- Faça fork do repositório desejado
- Siga nossos templates de Pull Request
- Garanta que testes passem e documentação esteja atualizada
- Aguarde revisão da equipe técnica

#### 📚 **Melhore a Documentação**

- Ajude a tornar nossos manuais mais claros
- Traduza documentação quando necessário
- Reporte inconsistências ou informações desatualizadas

### 🎯 **Áreas Prioritárias para Contribuição**

- 🏗️ **APIs e Microserviços** - Melhorias em performance e funcionalidades
- 🎨 **UI/UX** - Componentes de interface e experiência do usuário
- 🔒 **Segurança** - Auditoria de código e melhorias de segurança
- 📊 **Documentação** - Manuais técnicos e guias de usuário
- 🧪 **Testes** - Cobertura de testes e cenários edge cases

### ⚡ **Processo Simplificado**

1. **Explore** nossos repositórios e identifique algo interessante
2. **Leia** a documentação do projeto específico
3. **Abra uma issue** para discutir sua ideia (opcional, mas recomendado)
4. **Desenvolva** sua contribuição seguindo nossos padrões
5. **Submeta** um Pull Request usando nosso template
6. **Colabore** com nossa equipe durante a revisão

> 💡 **Dica:** Para contribuições grandes ou complexas, recomendamos abrir uma issue primeiro para discussão e alinhamento com a equipe.

---

## 📞 Contato

### 🏛️ **Equipe Técnica**

Para dúvidas, sugestões ou comunicação técnica com nossa equipe de desenvolvimento:

- 📧 **Desenvolvimento:** `desenvolvimento@anpd.gov.br`
- 🔐 **Segurança (Vulnerabilidades):** `ddss@anpd.gov.br`

### 🌐 **Canais Oficiais**

- 🏠 [**Site Oficial da ANPD**](https://www.gov.br/anpd)
- 📚 [**Portal de Transparência**](https://www.gov.br/anpd/pt-br/acesso-a-informacao)
- 👥 [**Participação Social**](https://www.gov.br/anpd/pt-br/acesso-a-informacao/participacao-social)

### ⚡ **Suporte Rápido**

- 💬 **Issues GitHub** - Para questões técnicas específicas de cada repositório
- 📱 **Ouvidoria** - Para feedback geral sobre serviços da ANPD

> 📝 **Nota:** Para questões de proteção de dados pessoais, consulte os [canais oficiais de atendimento](https://www.gov.br/anpd/pt-br/canais_atendimento/fale-conosco) da ANPD.

---

## 📊 Nossa Comunidade

### 🎯 **Estatísticas da Organização**

- 📦 **20+ repositórios** (11+ públicos, 9+ privados/forks)
- 🛠️ **4 linguagens principais** (TypeScript, JavaScript, Java, Python)
- 🏗️ **4 stacks tecnológicas** (React/Next.js, NestJS, Spring Boot, Quarkus)
- 🔄 **Templates padronizados** para toda a organização
- 🔐 **Políticas unificadas** de segurança e contribuição

### 🌟 **Tecnologias em Destaque**

- **Frontend:** React, Next.js, Material-UI (MUI), Storybook
- **Backend:** Node.js, NestJS, Java Spring Boot, Quarkus
- **Banco de Dados:** PostgreSQL, MS SQL Server, Prisma ORM
- **DevOps:** Docker, GitHub Actions, Dependabot
- **Qualidade:** ESLint, Prettier, TypeScript, Testes automatizados

### 🤝 **Contribuidores**

Agradecemos a todos os desenvolvedores, analistas e colaboradores que contribuem para fortalecer a cultura de proteção de dados no Brasil através do código aberto.

> 🌟 **Quer fazer parte?** Confira nossa seção [**Como Contribuir**](#-como-contribuir) e junte-se à nossa comunidade!

---

## 🏛️ Sobre a ANPD

A **Agência Nacional de Proteção de Dados** é a autarquia federal responsável por zelar pela proteção de dados pessoais no Brasil, garantindo a aplicação da **Lei Geral de Proteção de Dados Pessoais (LGPD)**.

### 🎯 **Nossa Missão Digital**

- 💻 **Código Aberto** como ferramenta de transparência pública
- 🛡️ **Proteção de Dados** através de tecnologia segura e auditável
- 🤝 **Colaboração** com a comunidade de desenvolvedores
- 🌐 **Interoperabilidade** com o ecossistema gov.br
- 📚 **Educação** sobre privacidade e proteção de dados

### 🏛️ Governança Digital

A ANPD instituiu o **Comitê de Governança Digital (CGD/ANPD)**, responsável por deliberar e acompanhar ações de governo digital e o uso de tecnologia da informação e comunicação (TIC) na Agência.

**Principais competências do Comitê:**

- Alinhar iniciativas de TI à estratégia institucional da ANPD.
- Deliberar e acompanhar objetivos, metas, planos, projetos e ações de TI.
- Definir e priorizar investimentos em tecnologia.
- Estabelecer diretrizes, normas e práticas de TI.
- Aprovar instrumentos de planejamento, como o **Plano Diretor de Tecnologia da Informação e Comunicação (PDTIC)**, o **Plano de Transformação Digital** e o **Plano de Dados Abertos**.
- Monitorar e prestar contas sobre a execução dos planos de TI, promovendo transparência ativa.
- Avaliar resultados e promover a melhoria contínua dos serviços digitais.

**Documentos e ações de referência:**

- [Resolução CD/ANPD nº 3/2023](https://www.in.gov.br/web/dou/-/resolucao-cd/anpd-n-3-de-25-de-janeiro-de-2023-460124477)
- [PDTIC/ANPD 2025-2028 (vigente)](https://www.gov.br/anpd/pt-br/acesso-a-informacao/acoes-e-programas/governanca/comite-governanca-digital/pdtic/pdtic-2025-2028-vigente.pdf)
- [Plano de Transformação Digital 2023-2024](https://www.gov.br/anpd/pt-br/acesso-a-informacao/acoes-e-programas/governanca/comite-governanca-digital/plano-de-transformacao-digital/ANPD_Plano_de_Transformacao_digital___24_assinado.pdf)
- [Processo de Desenvolvimento de Software](https://www.gov.br/anpd/pt-br/acesso-a-informacao/acoes-e-programas/governanca/comite-governanca-digital/comite-de-governanca-digital-1/ano-2025/documento-processo-de-desenvolvimento-de-software.pdf)
- [Estratégia de Uso de Software e Serviços de Computação em Nuvem](https://www.gov.br/anpd/pt-br/acesso-a-informacao/acoes-e-programas/governanca/comite-governanca-digital/Consolidado_ANPD_Estrategia_Nuvem.pdf)

**Princípios e compromissos:**

- Transparência ativa e prestação de contas.
- Modernização tecnológica e uso eficiente dos recursos públicos.
- Segurança da informação e proteção de dados pessoais.
- Adoção de soluções abertas sempre que legalmente possível.
- Participação social e alinhamento com as diretrizes do Governo Federal.

**Reuniões e atas públicas:** O Comitê se reúne trimestralmente e publica suas atas [neste link](https://www.gov.br/anpd/pt-br/acesso-a-informacao/acoes-e-programas/governanca/comite-governanca-digital).

### 🔗 **Links Úteis**

- 🏠 [Portal Oficial da ANPD](https://www.gov.br/anpd/pt-br/acesso-a-informacao/institucional)
- 📋 [Lei Geral de Proteção de Dados (LGPD)](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm)
- 🏆 [Prêmio Danilo Doneda](https://www.gov.br/anpd/pt-br/centrais-de-conteudo/concurso-de-monografias-da-anpd-premio-danilo-doneda)

---

> 💙 _"Por uma cultura de proteção de dados pessoais no Brasil."_
>
> **🇧🇷 Governo Federal do Brasil** | **🏛️ Agência Nacional de Proteção de Dados**

---

<div align="center">

[![GitHub Organization](https://img.shields.io/badge/GitHub-anpdgovbr-blue?style=for-the-badge&logo=github)](https://github.com/anpdgovbr)
[![Website](https://img.shields.io/badge/Website-gov.br%2Fanpd-green?style=for-the-badge&logo=firefox)](https://www.gov.br/anpd)
[![LGPD](https://img.shields.io/badge/LGPD-Compliance-gold?style=for-the-badge&logo=shield)](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm)

**⭐ Se nossos projetos são úteis para você, considere dar uma estrela nos repositórios!**

</div>

> ℹ️ **Nota:** Links externos abrem na mesma guia por padrão. Para abrir em nova guia, use o botão direito ou o atalho do navegador.
