# Avaliação

## 1 – Resolva o seguinte problema utilizando Java Swing:
- Crie uma tela que tenha 2 campos para entrada de números inteiros e um terceiro campo para apresentar o resultado.
- Esta tela deverá conter um botão “Enviar” e logo abaixo dele, um grid com 3 colunas, indicando os campos que foram preenchidos e o a outra coluna com o resultado. Estes valores irão ficar em memória, não sendo necessário salvar em banco de dados.

## 2- O botão enviar deverá consumir um serviço feito em Webservice, chamando o mesmo via Rest no padrão Json. Este serviço deverá retornar o resultado esperado da conta, conforme abaixo:
Dados 2 números, crie um retorno com a seguinte regra de retorno:
- O primeiro número de C é o primeiro número de A; 
- O segundo número de C é o primeiro número de B; 
- O terceiro número de C é o segundo número de A; 
- O quarto número de C é o segundo número de B;
 Assim sucessivamente… 
- Caso os números de A ou B sejam de tamanhos diferentes, completar C com o restante dos números do inteiro maior.
 Ex: A = 98754, B = 657, C deve ser 96857754. 
- Caso C seja maior que 1.000.000, retornar um erro informando que os valores ultrapassam o limite. (este erro não precisa ser adicionado no grid do swing).

## 3- No mesmo projeto do Webservice, criar 2 páginas em JPS, onde a primeira deverá ser uma tela com 2 campos (“login” e “senha”) com um botão “logar”. 
- Ao clicar no botão logar, ele deverá validar se o login é igual a “maria” e a senha é igual a “Maria”. 
- O Login não deverá ser sensitivecase, mas a senha sim.
- Após fazer o login, deverá ser encaminhado para uma pagina que irá mostrar todas as consultas feitas ao webservices pelo aplicativo feito em Swing. Nesta página deverá conter as entradas de valores os resultados e também os que deram erro.

## 4- Resolva os exercicios do documento "Avaliação Sql.docx"

