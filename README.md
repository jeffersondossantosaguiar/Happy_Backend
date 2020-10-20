<h1 align="center">Happy</h1>

<img src="https://raw.githubusercontent.com/rocketseat-education/nlw-03-omnistack/master/.github/happy.png" />

Backend do APP Happy desenvolvido na Next Level Week da Rocketseat

# Descrição

Happy é um projeto desenvolvido para criar um link entre casas de acolhimento e pessoas que desejam visitá-las. Onde é possível cadastrá-las e disponibilizar informações sobre visitação a regras sobre.

## Tecnologias 

Esse projeto foi desenvolvido com as seguintes tecnologias:

 - NodeJS
 - TypeScript
 
Libs usadas
 - [Yup](https://github.com/jquense/yup) - Yup é um JavaScript construtor de esquema para análise e validação de valor.

## Uso

### Instalação
``` bash
# Clonando o repositório
git clone https://github.com/jeffersondossantosaguiar/Happy_Backend.git

# Instalando dependências
npm install
````
### Executando
``` bash
npm run dev
````
URI padrão - http://localhost:3333/
### Consumindo

- Cadastro de orfanatos - POST - http://localhost:3333/orphanages
- Campos (todos obrigatórios):
	-  name: text
	-  latitude : text
	- longitude: text
	- about: text
	- images: file
	- instructions: text
	- opening_hours: text
	- open_on_weekends: text

- Listagem de orfanatos - GET - http://localhost:3333/orphanages
- Listagem de orfanato específico - GET - http://localhost:3333/orphanages/:id



