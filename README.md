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

Mais Exemplos:

- `feat`: (novo recurso para o usuário, não um novo recurso para script de construção)
- `fix`: (correção de bug para o usuário, não uma correção para um script de construção)
- `docs`: (mudanças na documentação)
- `style`: (formatação, ponto e vírgula ausente, etc.; nenhuma alteração no código de produção)
- `refactor`: (refatoração de código de produção, por exemplo, renomeação de uma variável)
- `test`: (adicionando testes ausentes, refatorando testes; nenhuma alteração no código de produção)
- `chore`: (atualizando tarefas pesadas etc.; nenhuma alteração no código de produção)

Referências:

- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html
