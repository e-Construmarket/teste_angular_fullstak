# Teste de Angular FullStak
Na raiz do repositório esta o layout final, que dever ser desenvolvido no front.

# DotNet
Criar API´S
- Criar um endpoint que receba usuário e senha, faça a validação desses dados e retorne um código token.
- Criar uma base de dados para cadastrar aluno e sua sala, deve ser relacionado. Um aluno pode ter várias salas e uma sala poderá ter vários alunos. Utilizar chave composta.
- Criar um endpoint protegido que retorne o nome do aluno e o nome da sala. Ex.: Rodrigo, Sala 2F.

- Criar endpoint para listagem de salas.
- Criar base de dados para cadastro de Sala, Tipo, Capacidade e Horário
  
# ANGULAR
Utilizar a versão 7 ou 8 do Angular.

Consiste em duas telas:
- Login
	- Criar login de acesso ao sistema.
    - Criar tela de login que consuma o endpoint passando usuário e senha. Após validação, utilizar o token no endpoint protegido que retorna os nome do aluno e da sala. Esses dados devem ser exibidos na tela.
	- Ao acessar deve ser redirecionado para a tela de lista de salas

- Listagem de Salas
	- Consumir endpoint de listagem de salas que o usuário esta fazendo parte.
	- Nome da sala, Tipo Capacidade e Horário	

## Entrega
Ao finalizar submeter o arquivo via pullrequest neste mesmo repositório. Informa a pessoa que lhe enviou o teste para verificação.

**Desenvolva da sua forma, sem adicionar itens prontos e desenvolvidos por terceiros. Boa sorte :)
