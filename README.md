# Formulário de Inscrição de Cursos

## User Story

**Como um administrador do sistema,**
**Eu quero criar um formulário de inscrição para cursos,**
**Para que eu possa cadastrar novos cursos com todas as informações necessárias.**

## Decisões Tomadas

### Propósito:
Garantir que os administradores possam cadastrar cursos de maneira eficiente e sem erros, fornecendo todas as informações necessárias para a criação dos cursos.

### Campos do Formulário:
- Nome do curso
- Descrição do curso
- Instrutor
- URL da imagem de capa
- Data de início (dd/mm/aaaa)
- Data de fim (dd/mm/aaaa)
- Número de vagas
- Tipo de curso (Presencial ou Remoto)
- Endereço (obrigatório apenas para cursos presenciais)
- Link (obrigatório apenas para cursos remotos)

### Validações:
- Todos os campos são obrigatórios.
- Datas devem estar no formato dd/mm/aaaa e a data de fim deve ser posterior à data de início.
- Número de vagas deve ser um número inteiro positivo.
- URL da imagem de capa deve ser uma URL válida.
- Tipo de curso deve ser selecionado entre "Presencial" e "Remoto".
- Endereço deve ser obrigatório apenas para cursos presenciais.
- Link deve ser obrigatório apenas para cursos remotos.

### Comportamento do Formulário:
- O botão "Enviar" é ativado somente após todos os campos obrigatórios serem preenchidos corretamente.
- Exibir mensagens de erro ao lado dos campos que não estiverem preenchidos corretamente.
- Exibir uma mensagem de sucesso após a criação do curso.

## Critérios de Aceitação
- Todos os campos devem ser preenchidos corretamente conforme as validações especificadas.
- Mensagens de erro claras e específicas devem ser exibidas em caso de dados inválidos.
- Mensagem de sucesso deve ser exibida após a criação do curso.
