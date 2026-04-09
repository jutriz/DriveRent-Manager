# DriveRent-Manager
Sistema de gestão de frota de veículos desenvolvido com React + TypeScript, com foco em roteamento, gerenciamento de estado e persistência de dados.

Acesse o projeto online:
https://zxnfnz.csb.app/

Editar no CodeSandbox:
https://codesandbox.io/s/zxnfnz

Funcionalidades
Cadastro de novos veículos
Listagem de veículos cadastrados
Remoção de veículos
Visualização de detalhes de cada veículo
Navegação entre páginas com React Router
Rotas protegidas (simulação de autenticação)
Persistência de dados com LocalStorage
Feedback visual durante cadastro (delay simulado)
Página 404 para rotas inválidas

Conceitos aplicados
React Hooks (useState, useEffect)
State Lifting
React Router DOM
Rotas aninhadas (Nested Routes)
Rotas dinâmicas (useParams)
Navegação programática (useNavigate)
Rotas protegidas
Componentização
Tipagem com TypeScript
Manipulação de formulários controlados

Estrutura do projeto
src/
 ├── components/
 │    ├── NavBar.tsx
 │    ├── RootLayout.tsx
 │    └── ProtectedRoute.tsx
 │
 ├── pages/
 │    ├── Home.tsx
 │    ├── VehicleRegister.tsx
 │    ├── FleetDashboard.tsx
 │    ├── VehicleDetails.tsx
 │    └── NotFound.tsx
 │
 ├── types/
 │    └── Veiculo.ts
 │
 ├── App.tsx
 ├── main.tsx
 └── styles.css

Interface

O projeto utiliza um tema visual em laranja e branco, com foco em simplicidade e usabilidade.

Tecnologias utilizadas
React
TypeScript
React Router DOM
CodeSandbox
HTML + CSS

Como executar
Acesse o link do CodeSandbox:
https://codesandbox.io/s/zxnfnz
O projeto já estará pronto para uso no navegador.

Desenvolvido por

Julia Chuery
