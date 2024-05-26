# Padrões de Commits Convencionais 📊

---

## Sumário 📚
1. [Introdução 📖](#1-introdução-📖)
2. [Importância da Padronização dos Commits 🔧](#2-importância-da-padronização-dos-commits-🔧)
3. [Como Usar Commits Convencionais? 📐](#3-como-usar-commits-convencionais-📐)
4. [Tipos de Commits 🗂️](#4-tipos-de-commits-🗂️)
5. [Exemplos 💡](#5-exemplos-💡)
6. [Como Contribuir? 🤝](#6-como-contribuir-🤝)
7. [Licença 📜](#7-licença-📜)
8. [Contato 📧](#8-contato-📧)

---

## 1. Introdução 📖
Commits Convencionais é uma especificação para escrever mensagens de commit consistentes. Ela define um conjunto de regras para criar um histórico de commits explícito, o que facilita a criação de ferramentas automatizadas. Esses padrões têm como objetivo melhorar a legibilidade e a estrutura das mensagens de commit, facilitando, assim, a colaboração e a gestão de projetos.

---

## 2. Importância da Padronização dos Commits 🔧
Padronizar os commits proporciona vários benefícios:
- **Melhora a legibilidade 🧾:** Mensagens de commit consistentes tornam mais fácil entender as mudanças feitas no projeto.
- **Facilita a colaboração 🤝:** Os membros da equipe podem rapidamente compreender o contexto das mudanças.
- **Automatiza tarefas 🔄:** Ferramentas podem gerar changelogs, notas de versão e números de versão automaticamente.
- **Aprimora a gestão do projeto 📈:** Mensagens de commit claras ajudam no acompanhamento do progresso e na identificação de problemas.

---

## 3. Como Usar Commits Convencionais? 📐
Para usar os Padrões de Commits Convencionais:
- **Adote um formato consistente 📏:** Siga a estrutura definida pelos Commits Convencionais.
- **Use mensagens significativas 📝:** Escreva mensagens de commit que descrevam claramente as mudanças feitas.
- **Aproveite as ferramentas 🛠️:** Utilize ferramentas que imponham ou validem as mensagens de Commits Convencionais, como o commitlint.

Formate suas mensagens de commit assim:
```
<tipo>[escopo (opcional)]: <descrição>
[body (opcional)]
[rodapé (opcional)]
```
- **Tipo**: Indica o tipo de mudança que o commit está fornecendo.
- **Escopo** (opcional): Um escopo pode ser incluído para fornecer informações contextuais adicionais e está contido entre parênteses, seguindo o tipo.
- **Descrição**: Uma descrição curta da mudança.
- **Corpo** (opcional): Uma descrição mais longa da mudança.
- **Rodapé** (opcional): Um ou mais rodapés que podem incluir avisos de "BREAKING CHANGE" ou referências a IDs de rastreamento de issues.

---

## 4. Tipos de Commits 🗂️
Os Padrões de Commits Convencionais incluem vários tipos, cada um servindo a um propósito específico:

- **fix 🐛**: Corrige um bug na sua base de código.
- **feat ✨**: Introduz uma nova funcionalidade na base de código.
- **docs 📝**: Apenas mudanças na documentação.
- **style 💅**: Mudanças que não afetam o significado do código (espaços em branco, formatação, falta de ponto e vírgula, etc).
- **refactor 🔨**: Uma mudança no código que nem corrige um bug nem adiciona uma funcionalidade.
- **perf ⚡**: Melhora o desempenho.
- **test 🧪**: Adiciona testes ausentes ou corrige testes existentes.
- **build 📦**: Mudanças que afetam o sistema de build ou dependências externas (escopos de exemplo: gulp, broccoli, npm).
- **ci 🚀**: Mudanças em arquivos de configuração e scripts de CI (escopos de exemplo: Travis, Circle, BrowserStack, SauceLabs).
- **chore 🧹**: Outras mudanças que não modificam arquivos src ou de teste.
- **wip 🚧**: Trabalho em andamento; ainda não está pronto para produção.

---

## 5. Exemplos 💡
Cada exemplo de mensagem de commit inclui um comando Bash para demonstrar como criar o commit usando Git.

### fix 🐛
```bash
git commit -m "fix(order): corrigir erros de digitação menores no código

ver a issue para detalhes sobre os erros de digitação corrigidos"
```
### feat ✨
```bash
git commit -m "feat(blog): adicionar seção de comentários

Os usuários agora podem deixar comentários nos artigos. Esta era uma funcionalidade muito solicitada pelo nosso feedback de usuários."
```
### docs 📝
```bash
git commit -m "docs(changelog): atualizar changelog para 0.3.0"
```
### style 💅
```bash
git commit -m "style(navbar): corrigir indentação"
```
### refactor 🔨
```bash
git commit -m "refactor(auth): simplificar lógica de validação"
```
### perf ⚡
```bash
git commit -m "perf(rendering): cachear ativos SVG"
```
### test 🧪
```bash
git commit -m "test(login): adicionar testes unitários para redefinição de senha"
```
### build 📦
```bash
git commit -m "build(packer): atualizar dependências"
```
### ci 🚀
```bash
git commit -m "ci(travis): forçar instalação de dependências"
```
### chore 🧹
```bash
git commit -m "chore(release): aumentar versão para 1.0.3"
```
### wip 🚧
```bash
git commit -m "wip(feature-x): commit temporário - to be squashed"
```

---

## 6. Como Contribuir? 🤝
Contribuições são bem-vindas! Se você tem um novo tipo de projeto para adicionar ou melhorias nos scripts existentes, sinta-se à vontade para fazer um fork do repositório e enviar um pull request. Por favor, siga as diretrizes abaixo:
- Faça um fork do repositório.
- Crie um novo branch (`git checkout -b feature-branch`).
- Faça suas alterações.
- Faça commit das suas alterações (`git commit -m "feat: adicionar nova funcionalidade"`).
- Faça push para o branch (`git push origin feature-branch`).
- Abra um pull request.

---

## 7. Licença 📜
Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENÇA](https://github.com/BrunoTanabe/conventional-commits-pattern/blob/main/LICENSE) para mais detalhes.

---

## 8. Contato 📧
Para quaisquer perguntas ou sugestões, por favor, abra uma issue no GitHub ou entre em contato com o proprietário do repositório em [tanabebruno@gmail.com](mailto:tanabebruno@gmail.com).

---
