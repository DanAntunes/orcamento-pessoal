# App Orçamento Pessoal

Este aplicativo é uma ferramenta prática para gerenciamento de despesas pessoais, desenvolvida durante um curso de desenvolvimento web.

## Funcionalidades

- **Adicionar Despesas**: Cadastre suas despesas fornecendo informações como data, tipo, descrição e valor. O aplicativo verifica se todos os campos foram preenchidos corretamente antes de salvar.
- **Listar Despesas**: Visualize todas as despesas registradas com opções de filtros por data, tipo, descrição e valor.
- **Excluir Despesas**: Remova facilmente despesas indesejadas.

## Detalhes Técnicos

### Classes JavaScript
- `Despesa`: Representa uma despesa com propriedades para data, tipo, descrição e valor.
- `Bd`: Gerencia as operações de armazenamento local, incluindo adicionar, recuperar e excluir despesas.

### Funções JavaScript
- `cadastrarDespesa()`: Valida os dados e salva a despesa no armazenamento local.
- `carregaListaDespesas()`: Atualiza e exibe a lista de despesas na interface.
- `pesquisarDespesa()`: Filtra as despesas listadas conforme critérios especificados pelo usuário.

### Front-end
- Utilização de **HTML** e **CSS** para criar uma interface de usuário intuitiva e responsiva.

## Observações Importantes

- **Armazenamento**: Utiliza o Local Storage do navegador para manter as despesas, que são armazenadas no formato JSON.
- **Segurança**: Não há sistema de autenticação, o que significa que qualquer pessoa com acesso ao navegador pode visualizar ou alterar as despesas.

---

Desenvolvido com ❤️ por Dan Antunes.
