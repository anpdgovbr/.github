# Configurações da Organização ANPD

Repositório especial `.github` da **Agência Nacional de Proteção de Dados (ANPD)**. Ele define o perfil público da organização e os arquivos de comunidade usados como padrão pelos repositórios públicos que não têm versões próprias.

O GitHub da ANPD é usado apenas para projetos publicados para uso externo e para forks de projetos de outros órgãos do governo federal.

---

## Estrutura

```
.
├── profile/
│   └── README.md             # Página inicial da organização
├── SECURITY.md               # Política de segurança
├── CONTRIBUTING.md           # Guia de contribuição
├── CODE_OF_CONDUCT.md        # Código de conduta
├── ISSUE_TEMPLATE/           # Templates padrão de issues
│   ├── bug_report.yml
│   ├── feature_request.yml
│   └── question.yml
├── pull_request_template.md  # Template padrão de PR
├── .github/
│   ├── dependabot.yml        # Atualização das Actions deste repositório
│   └── workflows/
│       └── validate-templates.yml  # Validação dos templates e links
└── README.md                 # Este arquivo
```

Os arquivos de comunidade (`SECURITY.md`, `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`) e os templates de issue e PR valem como padrão para os repositórios públicos da organização que não definem versões próprias. Os links entre eles usam URLs absolutas para funcionar em qualquer repositório.

---

## Como atualizar

1. Abra um **Pull Request** com as mudanças.
2. Solicite revisão da equipe de desenvolvimento.
3. Após a aprovação, faça o merge na `main`.

Ao mudar a lista de projetos públicos, atualize `profile/README.md` e os exemplos nos templates de issue.

---

## Contatos

- **Desenvolvimento:** desenvolvimento@anpd.gov.br
- **Segurança:** cosis.sgi@anpd.gov.br
- **Site oficial:** [www.gov.br/anpd](https://www.gov.br/anpd)

---

**Agência Nacional de Proteção de Dados – ANPD**
