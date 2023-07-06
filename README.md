Documentação da API - Sistema de Gerenciamento de Tarefas

• Rotas Disponíveis

Listar todas as tarefas:
GET /clientes
Retorna todas as tarefas cadastradas no sistema.

Obter detalhes de uma tarefa específica:
GET /clientes/{id}
Retorna os detalhes da tarefa com o ID especificado.

Criar uma nova tarefa:
POST /clientes
Cria uma nova tarefa no sistema.

Atualizar os dados de uma tarefa existente
PUT /clientes/{id}
Atualiza os dados da tarefa com o ID especificado.

Excluir uma tarefa
DELETE /clientes/{id}
Exclui a tarefa com o ID especificado.

• Parâmetros

Obter detalhes de uma tarefa específica:
id - ID da tarefa a ser recuperada.

Criar uma nova tarefa:
title - Título da tarefa.
description - Descrição da tarefa.
status - Status da tarefa.

Atualizar os dados de uma tarefa existente:
id - ID da tarefa a ser atualizada.
title - Novo título da tarefa.
description - Nova descrição da tarefa.
status - Novo status da tarefa.

Excluir uma tarefa:
id - ID da tarefa a ser excluída.

• Respostas

As respostas da API serão retornadas no formato JSON.


link do vídeo: https://youtu.be/fEhI9yAvaFU
