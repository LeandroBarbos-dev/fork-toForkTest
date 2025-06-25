Projeto Git Exercicios

Exercicios para praticar os comandos e funcionalidades do git.

Ações:

   Etapa 1:
	Criei o diretorio "projetos-git-exercicio" com git init
	Criei o arquivo README.md
	Usei git status para ver o status do diretorio
	Adicionei o README no versionamento com git add .
	Fiz o commit com git commit -m "Inicial"

   Etapa 2:
	Após escever a etapa 1, usei git status 
	Observei que o README.md foi editado, pois adicionei a etapa 1
	Então usei git add .
	Verifiquei com git status
	Dei commit com git commit -m "Etapa1"

   Etapa 3:
	Após escrever a etapa 2, usei git diff
	com git diff consegui ver as alterações da etapa 1 para a etapa 2
	Depois usei git status -> git add . -> git commit -m "Etapa-2" -> git status

   Etapa 4 - Brnchs (Branch secundaria)
	Após fazer commit da etapa 3 passei para o proximo passo
	Criei uma brench nova, Secundaria, usando git checkout -b Secundaria
	Criei um novo arquivo chamado "Arquivo_secundario"
	Agora vou fazer o commit dele junto com as novas auterações do README


**Anotação: voltei para branch secundaria, não fiz merge, então ela esta desatualizada em ralação a main e não tem a etapa 5. o que acontece se eu fizer merge agora?


   Etapa 5 - Merge (Branch main)
	Após commit da etapa 4 fiz o murge na branch main com a secundaria, trazendo as modificações para branch principal
	Criei um novo arquivo na branch main, vou dar commit e voltar para branch secundaria

   Etapa 6 - Conflito (Branch secundaria)
	Como escrito na anotação, fiz um murge na branch Secundaria
	Os dois arquivos tinham altrações que o outro não possuia
	Além disso, as auterações eram na mesma linha
	Resultado: Um pequeno conflito
	É simples de resolver, mas deve ser feito manualmente pelo usuario

- Leandro Barbosa Pessoa Alves 13/06/2025