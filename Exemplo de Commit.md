# 📜 Padrões de Commits Semânticos

Commits semânticos seguem uma convenção simples para criar mensagens claras e padronizadas, facilitando o entendimento das alterações no código e a automação de processos. Utilizar esse padrão ajuda sua equipe a identificar rapidamente o tipo de mudança realizada, como correções, novas funcionalidades, atualizações de documentação, melhorias de performance, entre outros.

## 🦄 Tipos de Commits

Cada commit deve começar com uma palavra-chave que indica o tipo de alteração:

- **feat**: Adiciona um novo recurso.
- **fix**: Corrige um bug.
- **docs**: Atualiza a documentação.
- **test**: Altera ou adiciona testes.
- **build**: Modifica arquivos de build ou dependências.
- **perf**: Melhora a performance.
- **style**: Ajusta formatação, espaços, lint, etc. (sem alteração de código).
- **refactor**: Refatora o código sem alterar funcionalidades.
- **chore**: Atualiza tarefas de build, configurações ou pacotes.
- **ci**: Altera configurações de integração contínua.
- **raw**: Modifica arquivos de dados ou configurações.
- **cleanup**: Remove código comentado ou desnecessário.
- **remove**: Exclui arquivos, diretórios ou funcionalidades obsoletas.

## 📝 Estrutura da Mensagem

- **Tipo**: Palavra-chave do commit.
- **Descrição**: Breve explicação da alteração (máximo 4 palavras na primeira linha).
- **Corpo**: Detalhes sobre o que foi alterado, impactos e instruções futuras.
- **Rodapé**: Informações sobre revisor ou referência de tarefas (opcional).

Exemplo:
```
feat: página de login

Adiciona tela de login com validação de campos.
Reviewed-by: Nome do Revisor
Refs #123
```

## 💈 Emojis para Commits

Utilize emojis para identificar rapidamente o tipo de commit:

| Tipo           | Emoji         | Palavra-chave |
|----------------|--------------|--------------|
| Novo recurso   | ✨ :sparkles: | feat         |
| Bugfix         | 🐛 :bug:      | fix          |
| Documentação   | 📚 :books:    | docs         |
| Testes         | 🧪 :test_tube:| test         |
| Build          | 📦 :package:  | build        |
| Performance    | ⚡ :zap:      | perf         |
| Refatoração    | ♻️ :recycle:  | refactor     |
| Estilo         | 💄 :lipstick: | style        |
| Limpeza        | 🧹 :broom:    | cleanup      |
| Remoção        | 🗑️ :wastebasket: | remove   |
| Configuração   | 🔧 :wrench:   | chore        |
| Integração     | 🧱 :bricks:   | ci           |
| Comentários    | 💡 :bulb:     | docs         |
| Responsividade | 📱 :iphone:   | feat         |
| Deploy         | 🚀 :rocket:   | chore        |

## 💻 Exemplos de Commits

```shell
git commit -m ":tada: Commit inicial"
git commit -m ":books: docs: Atualização do README"
git commit -m ":bug: fix: Corrige loop infinito"
git commit -m ":sparkles: feat: Página de login"
git commit -m ":recycle: refactor: Refatora funções"
git commit -m ":zap: perf: Melhora tempo de resposta"
git commit -m ":lipstick: feat: Estilização CSS"
git commit -m ":test_tube: test: Adiciona novo teste"
git commit -m ":broom: cleanup: Remove código comentado"
git commit -m ":wastebasket: remove: Exclui arquivos obsoletos"
```

## 🛠️ Como Validar Mensagens de Commit

1. **Verifique se o Git está instalado**
   ```shell
   git --version
   ```

2. **Localize o arquivo commit-msg.sh**  
   Baixe ou copie para seu projeto.

3. **Crie o diretório de hooks (se necessário)**
   ```shell
   mkdir -p .git/hooks
   ```

4. **Copie e renomeie o script**
   ```shell
   cp caminho/para/commit-msg.sh .git/hooks/commit-msg
   ```

5. **Dê permissão de execução**
   ```shell
   chmod +x .git/hooks/commit-msg
   ```

6. **Teste o hook**
   ```shell
   git add .
   git commit -m "feat: adicionar funcionalidade xyz"
   ```

## 🎉 Recomendações

- Use tipos consistentes e claros.
- Mantenha a primeira linha curta e objetiva.
- Detalhe alterações no corpo do commit.
- Utilize emojis para facilitar a identificação visual.
- Evite links encurtados ou afiliados.

## 📜 Principais Comandos Git

- `git clone <url>`: Clona um repositório remoto.
- `git init`: Inicializa um novo repositório.
- `git add .`: Adiciona todas as alterações para commit.
- `git commit -m "mensagem"`: Realiza um commit.
- `git branch -M main`: Renomeia a branch principal.
- `git remote add origin <url>`: Adiciona repositório remoto.
- `git push -u origin main`: Envia commits para o remoto.
- `git fetch`: Busca atualizações do remoto.
- `git pull origin main`: Atualiza branch local.
- `git push --force-with-lease`: Força envio de alterações.
- `git revert <id_commit>`: Desfaz alterações de um commit.
- `git reset --hard <id_commit>`: Redefine para um commit anterior.
- `git commit --amend -m "nova mensagem"`: Altera mensagem do último commit.
- `git cherry-pick <hash>`: Aplica commit específico em outra branch.
- `git switch <branch>`: Troca de branch.

## 📖 Glossário

- **fork**: Cópia de um repositório para sua conta.
- **issues**: Gerenciamento de tarefas e bugs.
- **pull request**: Solicitação de revisão e inclusão de alterações.
- **gist**: Compartilhamento rápido de trechos de código.

---

> Domine os padrões de commit para garantir um histórico claro, organizado e colaborativo em seus projetos!