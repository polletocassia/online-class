# Decisões Arquiteturais

### 1. Arquitetura em Camadas

Optou-se pela utilização da **arquitetura em camadas**, dividindo o sistema em **Frontend Web**, **Backend/API**, **Banco de Dados** e **Serviço de IA**. Essa abordagem facilita a organização do projeto, a manutenção do código e atende adequadamente às necessidades do MVP proposto.

### 2. Integração com Serviço de IA

A funcionalidade de **Inteligência Artificial** foi definida como um serviço independente integrado ao sistema por meio do Backend/API. Essa separação permite evoluir os recursos de correção automática e geração de relatórios sem impactar as demais funcionalidades da plataforma.

### 3. Autenticação e Controle de Permissões

O sistema utilizará autenticação de usuários e controle de permissões para diferenciar os perfis de **Professor** e **Aluno**. Essa decisão garante que cada usuário tenha acesso apenas às funcionalidades compatíveis com suas responsabilidades e regras de negócio.

### 4. Centralização dos Dados

Todas as informações da plataforma serão armazenadas em um banco de dados centralizado, incluindo usuários, turmas, atividades, entregas, notas, mensagens e dados da gamificação. Essa decisão contribui para a organização, integridade e disponibilidade das informações.