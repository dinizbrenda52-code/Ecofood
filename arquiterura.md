Arquitetura do Sistema
O sistema EcoFood foi projetado como uma aplicação web com arquitetura cliente-servidor, separando responsabilidades entre frontend, backend e banco de dados.

Modelo Arquitetural (C4)
Nível C1 – Diagrama de Contexto
O sistema EcoFood interage com:
Usuário: utiliza o sistema para gerenciar alimentos
Sistema de Notificação: responsável pelo envio de alertas
Nível C2 – Diagrama de Containers
O sistema é composto por:
Frontend (Web): Interface do usuário (responsável pela interação com o usuário)
Backend (API) : Processamento das regras de negócio (gerenciamento dos dados)
Banco de Dados: Armazenamento de usuários e alimentos

Tecnologias Escolhidas
Frontend: HTML, CSS, JavaScript
Backend: Node.js
Banco de Dados: MongoDB

Justificativa das Escolhas
A arquitetura cliente-servidor foi escolhida por:
- Separar responsabilidades entre interface e lógica
- Facilitar manutenção e escalabilidade
- Permitir evolução independente entre frontend e backend
O uso de Node.js permite desenvolvimento rápido e integração eficiente com aplicações web.
O MongoDB foi escolhido por sua flexibilidade no armazenamento de dados não estruturados.
