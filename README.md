Questão 1 -> Está dentro do projeto no Visual Studio
Instruções
Passo 1 - Abrir o Program.cs e entrar com os dados abaixo:

Exemplo 1:

Entre o número da conta: 5447
Entre o titular da conta: Milton Gonçalves
Haverá depósito inicial(s / n) ? s
Entre o valor de depósito inicial: 350.00

Dados da conta:
Conta 5447, Titular: Milton Gonçalves, Saldo: $ 350.00

Entre um valor para depósito: 200
Dados da conta atualizados:
Conta 5447, Titular: Milton Gonçalves, Saldo: $ 550.00

Entre um valor para saque: 199
Dados da conta atualizados:
Conta 5447, Titular: Milton Gonçalves, Saldo: $ 347.50

Exemplo 2:
Entre o número da conta: 5139
Entre o titular da conta: Elza Soares
Haverá depósito inicial(s / n) ? n

Dados da conta:
Conta 5139, Titular: Elza Soares, Saldo: $ 0.00

Entre um valor para depósito: 300.00
Dados da conta atualizados:
Conta 5139, Titular: Elza Soares, Saldo: $ 300.00

Entre um valor para saque: 298.00
Dados da conta atualizados:
Conta 5139, Titular: Elza Soares, Saldo: $ -1.50

---------------------------------------------------------------------------------------------------------------------------------

Questão 2 -> Está dentro do projeto no Visual Studio (
Instruções
Passo 1 - Botão direito nela e clica em Configure Startup Projects
Passo 2 - Escolhe a opção no combo -> Multiple startup projects e deixar a Action Start nos projects (Questao2Api e Questao2)
Passo 3 - Clicar em Aplicar e depois no botão OK.

---------------------------------------------------------------------------------------------------------------------------------

Questão 3 -> A resposta está na pasta do teste e também aqui abaixo:

Ao final dessa sequência de comandos, os arquivos que se encontram em seu diretório de trabalho, além do README.md, é/são:

•	[      ] script.js e style.css, apenas.
•	[      ] default.html e style.css, apenas.
•	[   X   ] style.css, apenas.
•	[      ] default.html e script.js, apenas.
•	[      ] default.html, script.js e style.css.

---------------------------------------------------------------------------------------------------------------------------------

Questão 4 -> A resposta está na pasta do teste e também aqui abaixo:

SELECT A.ASSUNTO, A.ANO, COUNT(A.ASSUNTO) AS QUANTIDADE
FROM atendimentos A
GROUP BY A.ASSUNTO, A.ANO
HAVING COUNT (A.ASSUNTO) > 3
ORDER BY A.ANO DESC, A.ASSUNTO DESC;

---------------------------------------------------------------------------------------------------------------------------------

Questão 5 -> Está dentro do projeto no Visual Studio

Obs: Dentro da Solution -> Exercicio -> Criei uma nova API -> Questao2Api -> Swagger com o endpoint da questão 2 do Word.  

Serviço: Movimentação de uma conta corrente

Massa de teste

-- CRÉDITO
{
  "idContaCorrente": "B6BAFC09-6967-ED11-A567-055DFA4A16C9",
  "dataMovimento": "2025-06-24",
  "tipoMovimento": "C",
  "valor": 90
}

-- DÉBITO
{
  "idContaCorrente": "B6BAFC09-6967-ED11-A567-055DFA4A16C9",
  "dataMovimento": "2025-06-24",
  "tipoMovimento": "D",
  "valor": 30.50
}

---------------------------------------------------------------------------------------------------------------------------

Serviço: Saldo da conta corrente

Massa de teste

B6BAFC09-6967-ED11-A567-055DFA4A16C9
