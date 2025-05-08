# 🧾 Guia de Padronização de Commits

> Padrão baseado no [Conventional Commits](https://www.conventionalcommits.org/), com melhorias para clareza e organização do histórico de mudanças.

---

## 📌 Estrutura do Commit

```bash
<tipo>: <descrição clara e objetiva no imperativo>
```
## 🧠 Prefixos mais utilizados

| Tipo       | Emoji | Quando usar                                                             |
| ---------- | ----- | ----------------------------------------------------------------------- |
| `feat`     | ✨     | Nova funcionalidade                                                     |
| `fix`      | 🐛    | Correção de bug                                                         |
| `style`    | 💄    | Alterações de estilo (espaços, indentação, formatação, ponto e vírgula) |
| `refactor` | 🔨    | Refatoração de código (sem alterar comportamento externo)               |
| `perf`     | ⚡     | Melhorias de performance                                                |
| `test`     | ✅     | Adição ou alteração de testes                                           |
| `docs`     | 📝    | Mudanças em documentação (README, comentários, etc)                     |
| `chore`    | 🔧    | Tarefas de manutenção e updates não relacionados ao código em si        |
| `ci`       | 🤖    | Alterações em pipelines de CI/CD                                        |
| `build`    | 🛠️   | Alterações no processo de build, dependências ou ferramentas            |

## 🧰 Exemplos práticos

feat: criar endpoint de autenticação via token 

fix: corrigir erro de login com email inválido 

style: aplicar Prettier em todos os arquivos JS

refactor: extrair método de validação para helper

perf: melhorar tempo de resposta da listagem de produtos 

test: adicionar teste para componente de botão 

docs: atualizar instruções de instalação no README 

chore: atualizar dependências com npm update 

ci: corrigir configuração do GitHub Actions 

build: ajustar script de build para ambiente de staging 

## 🧼 Dicas para uma boa descrição
Use verbos no imperativo (ex: "adicionar", "corrigir", "remover", "refatorar").

Seja curto e claro: máximo 72 caracteres na primeira linha.

Se precisar detalhar mais, adicione um corpo após a linha principal

## ✅ Commit perfeito

refactor: reorganizar parâmetros e remover duplicações em swfuploadAction

Ajustado para evitar repetição desnecessária de código.

Parâmetros foram movidos para o topo da função.
