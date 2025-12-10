# Projeto-Dark-Souls-2-Check-list-app

- Projeto de um aplicativo em kotlin para android que separa as categorias de alguns itens do Dark Souls 2: Scholar of the first Sin.
- Ideia é ser um organizador para a platina do jogo.

**O projeto contém atividades bem manuais como o o json preenchido item por item, a ideia é exercicitar a estrutura do arquivo e atividades com o uso dele.**

# Fluxo
1. Carrega Json
2. Exibe Categorias
3. Lista itens
4. Salva progresso
5. Detalhes

# Estrutura Do Json

Categoria
|
|--Feitiços
|  |-- Todos os feitiços do jogo
|       |-- Id, nome, descrição, requerimentos, como obter, ngPlus, obteve
|
|--Piromancias
|  |-- Todos as piromancias do jogo
|       |-- Id, nome, descrição, requerimentos, como obter, ngPlus, obteve
|
|--Milagres
|  |-- Todos os milagres do jogo
|       |-- Id, nome, descrição, requerimentos, como obter, ngPlus, obteve
|
|--Bosses
|  |-- Todos os bosses do jogo
|       |-- Id, nome, descrição,como obter, ngPlus, obteve
|
|--Coletaveis
|  |-- Todos os coletaveis do jogo
|       |-- Id, nome, descrição,como obter, ngPlus, obteve
|
|--Resto
|  |-- Tudo que sobrou em relação as cetegorias como estus no maximo, etc.
|       |-- Id, nome, descrição, como obter, ngPlus, obteve
|

# Estrutura do projeto
