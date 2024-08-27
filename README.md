# orderManagement

<p>Este projeto tem por finalidade testar minhas capacidades com logica de programação, comunicação entre sistemas e etc.</p>

<h2>Detalhamento do Projeto:</h2>

<p>
  
  <h2>Requisitos Gerais:</h2>

O sistema deve permitir o gerenciamento de pedidos de forma eficiente e organizada.
Deve haver 3 níveis de acesso: Administradores, Gerentes e Associados.
Cada nível de acesso terá permissões e funcionalidades específicas no sistema.

Módulo de Gerenciamento de Acessos:

O sistema deve ter um módulo dedicado ao gerenciamento de acessos e permissões.

<h3>Neste módulo, os Administradores poderão:</h3>

Criar, editar e desativar contas de usuários.
Atribuir os níveis de acesso (Administrador, Gerente ou Associado) para cada usuário.
Definir e gerenciar as permissões específicas para cada nível de acesso.
Os Gerentes e Associados não terão acesso a este módulo, apenas visualização de suas próprias informações de perfil.

<h3>Módulo de Gerenciamento de Pedidos:</h3>

Neste módulo, todos os usuários (Administradores, Gerentes e Associados) poderão:
Visualizar a lista de pedidos.
Filtrar e pesquisar pedidos por diferentes critérios (número do pedido, data, cliente, status, etc.).
Visualizar os detalhes de um pedido específico.

<h3>Os Associados e Gerentes poderão:</h3>

Criar novos pedidos.
Atualizar o status de um pedido (ex: Novo, Em Andamento, Concluído, Cancelado).
Adicionar comentários e anexos aos pedidos.
Os Administradores terão acesso a todas as funcionalidades do módulo de Gerenciamento de Pedidos, além de:
Gerar relatórios e dashboards sobre os pedidos.
Monitorar e acompanhar os pedidos de acordo com as permissões atribuídas aos diferentes níveis de acesso.

<h3>Módulo de Gerenciamento de Chamados:</h3>

<h4>Neste módulo, os Associados e Gerentes poderão:</h4>

Criar novos chamados relacionados a um pedido.
Atribuir o chamado a uma área ou departamento específico da empresa.
Acompanhar o status e o andamento do chamado.
Adicionar comentários e anexos aos chamados.

<h3>Os Administradores poderão:</h3>

Visualizar todos os chamados criados.
Reatribuir chamados entre as áreas e departamentos.
Gerar relatórios e dashboards sobre os chamados.

</p>

# Principais tecnologias utilizadas:

<ul>
  <li>Java 17, 18, 22</li>
  <li>PHP 8</li>
  <li>Python 3.12</li>
  <li>SQL</li>
</ul>

<h3>Frameworks</h3>

<ul>
  <li>Spring</li>
  <li>Djnago</li>
  <li>Laravel</li>
</ul>
