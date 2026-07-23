# 🏛️ Configurações da Organização ANPD

Este é o repositório especial `.github` da **Agência Nacional de Proteção de Dados (ANPD)** que contém as configurações padrão da organização, templates e políticas aplicáveis a todos os nossos repositórios.

---

## 📁 Estrutura do Repositório

```
.github/
├── profile/                          # Perfil público da organização
│   ├── README.md                     # Página inicial da organização
│   ├── CONTRIBUTING.md               # Guia de contribuição
│   ├── CODE_OF_CONDUCT.md           # Código de conduta
│   └── SECURITY.md                  # Política de segurança
├── ISSUE_TEMPLATE/                   # Templates para issues
│   ├── bug_report.yml               # Template para bugs
│   ├── feature_request.yml          # Template para funcionalidades
│   └── question.yml                 # Template para perguntas
├── workflows/                        # GitHub Actions workflows
│   └── validate-templates.yml       # Validação de templates
├── pull_request_template.md         # Template padrão para PRs
├── dependabot.yml                   # Configuração do Dependabot
├── FUNDING.yml                      # Configuração de funding
└── README.md                        # Este arquivo
```

---

## 🎯 Propósito

### 📋 Templates Padronizados

- **Issues**: Templates específicos para bugs, funcionalidades e perguntas
- **Pull Requests**: Template abrangente com checklist completo
- **Contexto ANPD**: Todos os templates incluem considerações específicas da ANPD/LGPD

### 🔐 Políticas de Segurança

- **Divulgação responsável** de vulnerabilidades
- **Contatos específicos** para questões de segurança
- **Processo estruturado** de análise e correção

### 🤝 Código de Conduta

- Baseado no **Contributor Covenant 2.0**
- Adaptado para **organizações públicas**
- **Processo claro** de aplicação e escalação

### ⚙️ Automação

- **Dependabot** configurado para atualizações automáticas
- **Workflows** para validação de templates
- **Horários brasileiros** para notificações

---

## 🚀 Como Usar

### Para Novos Repositórios

1. Os templates são **aplicados automaticamente** a novos repositórios
2. O **SECURITY.md** pode ser copiado/adaptado conforme necessário
3. **Workflows** podem ser reutilizados como base

### Para Repositórios Existentes

1. **Copie** os arquivos relevantes para o repositório específico
2. **Adapte** o conteúdo conforme a especificidade do projeto
3. **Mantenha** a consistência com as políticas organizacionais

---

## 📝 Personalizações por Projeto

Alguns repositórios podem precisar de adaptações específicas:

### `shared-ui` e `shared-types`

- Templates de issues específicos para **componentes** e **tipos**
- Considerações de **compatibilidade** e **breaking changes**
- **Storybook** e documentação de componentes

### `cadastro-controladores-api` e `backlog-dim`

- Templates focados em **APIs** e **funcionalidades**
- Considerações de **migração de dados**
- **Testes de integração** e **performance**

### Projetos de Infraestrutura

- Templates para **Docker** e **DevOps**
- **Security** com foco em **infraestrutura**
- **Monitoramento** e **alertas**

---

## 🔄 Atualizações

### Quando Atualizar

- 📚 Mudanças nas **políticas internas** da ANPD
- 🔐 Novas **diretrizes de segurança**
- 🎯 **Feedback** da comunidade de desenvolvedores
- ⚙️ **Melhorias** nos processos de contribuição

### Como Atualizar

1. 🔀 Abra um **Pull Request** com as mudanças
2. 📋 Use o template de PR padrão
3. 👥 Solicite **revisão** da equipe de desenvolvimento
4. 🚀 Após aprovação, faça **merge** para `main`

### Propagação para Repositórios

- 📢 **Comunique** mudanças importantes via issues
- 📄 **Atualize** repositórios específicos conforme necessário
- 🔄 **Mantenha** consistência entre projetos

---

## 📊 Métricas e Monitoramento

### Templates de Issues

- 📈 **Taxa de uso** dos templates
- 📝 **Qualidade** das informações fornecidas
- ⏱️ **Tempo** de resolução por tipo

### Pull Requests

- ✅ **Taxa de aprovação** primeira revisão
- 🔄 **Número médio** de revisões
- 📋 **Completude** do checklist

### Segurança

- 🚨 **Número** de vulnerabilidades reportadas
- ⏰ **Tempo** de resposta inicial
- 🔒 **Tempo** de resolução

---

## 🤝 Contribuindo

Para sugerir melhorias neste repositório:

1. 📝 **Abra uma issue** usando o template apropriado
2. 💡 **Descreva** a melhoria sugerida
3. 🏛️ **Considere** o impacto em toda a organização
4. 🔄 **Aguarde** feedback da equipe

### Tipos de Contribuições Bem-vindas

- 📋 **Melhorias** nos templates
- 🔐 **Atualizações** de segurança
- 📚 **Documentação** mais clara
- ⚙️ **Automações** úteis
- 🎨 **Melhorias** na experiência do contribuidor

---

## 📞 Contatos

- 📧 **Desenvolvimento**: desenvolvimento@anpd.gov.br
- 🔐 **Segurança**: cosis.sgi@anpd.gov.br
- 🌐 **Site oficial**: [www.gov.br/anpd](https://www.gov.br/anpd)

---

## 📜 Licença

Este repositório segue as mesmas políticas de licenciamento dos demais projetos da ANPD. Consulte o arquivo `LICENSE` em cada repositório específico para detalhes.

---

**Agência Nacional de Proteção de Dados – ANPD**  
_"Por uma cultura de proteção de dados pessoais no Brasil."_
