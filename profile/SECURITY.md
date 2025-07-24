# 🔐 Política de Segurança da ANPD

Esta política de segurança aplica-se a todos os repositórios da **Autoridade Nacional de Proteção de Dados (ANPD)** e segue diretrizes públicas de desenvolvimento seguro.

Embora nossos projetos sejam de código aberto, **o foco principal é o uso e manutenção por equipes internas da ANPD e parceiros governamentais**.

---

## 📣 Como Reportar uma Vulnerabilidade

Caso você identifique uma possível vulnerabilidade de segurança em qualquer repositório da ANPD, **por favor, não abra uma issue pública**.

Em vez disso, envie um e-mail diretamente para nossa equipe técnica:

📧 **ddss@anpd.gov.br**

### 📋 Informações a Incluir

Para facilitar a análise e acelerar a resposta, inclua:

- **Repositório afetado** e versão/commit específico
- **Descrição detalhada** da vulnerabilidade
- **Passos para reprodução** (se aplicável)
- **Impacto potencial** da vulnerabilidade
- **Sugestões de correção** (se houver)
- **Suas informações de contato** para acompanhamento

### ⏰ Nosso Compromisso

Nos comprometemos a:

- ✅ Responder dentro de **5 dias úteis**
- ✅ Tratar o relatório de forma **confidencial**
- ✅ Fornecer atualizações sobre o progresso da análise
- ✅ Divulgar a correção de maneira **responsável**, se aplicável
- ✅ Reconhecer sua contribuição (se desejar)

---

## 📦 Versões Suportadas

| Projeto                      | Versões Suportadas | Status       |
| ---------------------------- | ------------------ | ------------ |
| `shared-ui`                  | Última versão      | ✅ Suportado |
| `shared-types`               | Última versão      | ✅ Suportado |
| `cadastro-controladores-api` | Última versão      | ✅ Suportado |
| `backlog-dim`                | Última versão      | ✅ Suportado |

> **Nota:** Apenas as versões **mais recentes** dos repositórios são oficialmente suportadas e monitoradas para correções de segurança.

---

## 🔒 Práticas de Segurança Recomendadas

### Para Contribuidores

- 🔐 **Nunca** commite credenciais, tokens ou chaves de API
- 🧪 Execute testes de segurança localmente quando possível
- 📚 Mantenha dependências atualizadas
- 🔍 Revise código de terceiros antes da integração

### Para Mantenedores

- 🛡️ Configure **Dependabot** para atualizações automáticas
- 🔒 Use **branch protection rules** em repositórios críticos
- 📊 Monitore **security advisories** do GitHub
- 🔑 Implemente **autenticação 2FA** obrigatória

---

## 📢 Divulgação Responsável

Após a análise e resolução da vulnerabilidade, publicaremos as correções via:

- 📝 **Histórico de commits** e changelog do projeto
- 🐛 **GitHub Security Advisories** para vulnerabilidades críticas
- 📋 **Issues públicas** com detalhes não sensíveis, se necessário
- 🏢 **Comunicação interna** via DDSS/CGTI/ANPD, se aplicável

### 🕐 Timeline de Divulgação

1. **Dia 0:** Recebimento do relatório
2. **Dia 1-5:** Confirmação e análise inicial
3. **Dia 5-30:** Desenvolvimento da correção
4. **Dia 30-90:** Teste e implementação
5. **Pós-correção:** Divulgação pública responsável

---

## 🏆 Programa de Reconhecimento

Reconhecemos e valorizamos pesquisadores de segurança que:

- 🎯 Reportam vulnerabilidades de forma responsável
- 🤝 Seguem nossa política de divulgação
- 💡 Fornecem detalhes técnicos úteis
- ⏰ Respeitam nossos timelines de correção

### 🙏 Formas de Reconhecimento

- 📜 **Hall of Fame** em nosso README organizacional
- 🏷️ **Menção** em security advisories (se desejar)
- 📧 **Carta de agradecimento** oficial da ANPD
- 🤝 **Convite** para participar de discussões técnicas futuras

---

## 🤝 Agradecimentos

Agradecemos a qualquer colaborador que reporte vulnerabilidades de forma responsável, ajudando a manter nossos sistemas mais seguros para toda a administração pública brasileira.

**Juntos, fortalecemos a cultura de proteção de dados no Brasil.**

---

## 📞 Contatos

- 📧 **Segurança:** ddss@anpd.gov.br
- 📧 **Desenvolvimento:** desenvolvimento@anpd.gov.br
- 🌐 **Site oficial:** [www.gov.br/anpd](https://www.gov.br/anpd)

---

**Divisão de Desenvolvimento e Sustentação de Sistemas (DDSS)**  
**Coordenação-Geral de Tecnologia da Informação (CGTI)**  
**Autoridade Nacional de Proteção de Dados – ANPD**
