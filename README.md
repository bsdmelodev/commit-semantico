# Mensagens de Commit Semântico

Veja como uma pequena mudança no estilo da sua mensagem de commit pode torná-lo um programador melhor.

Formatar: `<type>(<scope>): <subject>`

`<scope>` é opcional

## Exemplo

```
feat: add controller invoices
^--^  ^------------^
|     |
|     +-> Sumário no Presente
|
+-------> Tipos: chore, docs, feat, fix, refactor, style, or test.
```

## Padrão de Commits Semânticos

Para manter um histórico claro e organizado, seguimos o padrão de commits semânticos:

| Tipo       | Quando usar                                               | Exemplo de commit                                       |
|------------|----------------------------------------------------------|--------------------------------------------------------|
| `feat`     | Nova funcionalidade                                      | `feat(login): adicionar autenticação com Google`       |
| `fix`      | Correção de bug                                         | `fix(api): corrigir timeout na requisição`            |
| `docs`     | Alterações na documentação                               | `docs(readme): atualizar instruções de instalação`    |
| `style`    | Formatação, estilo ou pequenas melhorias sem alterar lógica | `style(button): ajustar espaçamento e cores`         |
| `refactor` | Melhorias ou reorganização de código sem mudar funcionalidade | `refactor(usuario): otimizar função de cálculo`       |
| `test`     | Adição ou alteração de testes                            | `test(auth): adicionar testes de login`               |
| `chore`    | Tarefas de manutenção, builds, dependências, etc.       | `chore(deps): atualizar biblioteca de segurança`      |

### Dicas rápidas
- Use **descrição curta e clara**.  
- Prefira **imperativo**, como “adicionar”, “corrigir”, “otimizar”.  
- O **escopo** entre parênteses é opcional, mas ajuda a identificar o módulo ou parte do código afetada.

## Referências:

- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html
