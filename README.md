# Gestao-Universitaria-UML

## Descrição

Este documento apresenta a análise do diagrama de caso de uso e a descrição detalhada dos cenários para um sistema de gestão de banco de dados, com foco em cadastros de diferentes tipos de pessoas. O objetivo é fornecer uma visão clara e abrangente das funcionalidades do sistema, facilitando o desenvolvimento e a implementação.

*1. Cadastro de Pessoas (Física, Professores, Alunos, Fornecedores):*
- Usuário autorizado acessa a tela de cadastro.
- Preenche os campos obrigatórios (nome, CPF/CNPJ, endereço, etc.), com campos específicos para cada tipo (curso para alunos, disciplinas para professores, produtos para fornecedores).
- Clica em "Salvar".
- O sistema valida os dados e salva no banco de dados.
- Exibe mensagem de sucesso.

*2. Visualização de Dados*
*Cenário Principal:*
- Usuário acessa a tela de visualização.
- Seleciona o tipo de dado (administrador, pessoa física, etc.).
- O sistema exibe a lista de registros.

*3. Edição de Cadastros*
- Usuário seleciona o registro para editar.
- Realiza alterações e clica em "Salvar".
- O sistema atualiza o registro.
- Exibe mensagem de sucesso.

*4. Exclusão de Cadastros*
- Usuário seleciona o registro para excluir.
- Confirma a exclusão.
- O sistema exclui o registro.
- Exibe mensagem de confirmação.
