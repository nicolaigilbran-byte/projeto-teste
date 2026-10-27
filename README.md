Relatório de Aprendizado: Git, Branches e Commits Semânticos

O que são Branches?
Uma branch é uma ramificação do código que permite desenvolver funcionalidades ou corrigir erros em isolamento, sem afetar a versão estável do projeto.

- **Branch `main`:** Mantém a versão estável e pronta para produção do software.
- **Branches de Desenvolvimento (`feat/*`, `fix/*`): Ramificações temporárias para criar novas funcionalidades ou correções antes de serem integradas na `main`.

 O que são Commits Semânticos?
São padrões de mensagens de commit que facilitam a leitura do histórico do projeto por toda a equipa:
- `feat`: Nova funcionalidade.
- `fix`: Correção de erro.
- `docs`: Alteração de documentação.
- `style`: Ajustes de formatação ou visual sem alterar o comportamento do código.

Comandos Utilizados
- `git checkout -b <nome>`: Cria e altera para uma nova branch.
- `git commit -m "<tipo>: <descrição>"`: Salva as alterações com uma mensagem padronizada.
- `git merge <nome>`: Integra os commits da branch especificada na branch atual.
- `git push origin <nome>`: Envia a branch para o repositório remoto (GitHub).

