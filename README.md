# RentalX - Ignite
---
Projeto desenvolvido durante a trilha Ignite - NodeJS

## Camadas
- Rotas:
  * cuida das rotas
  * não deve conhecer o modelo dos dados
  
- Repositórios: 
  * cuidam da manipulação dos dados (inserção em banco de dados, etc...)
  * deve conhecer os modelos dos dados

## Fluxo
1) Rota chama o Repositório
2) Repositório retorna para a Rota o que ela precisa