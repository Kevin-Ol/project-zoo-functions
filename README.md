# Projeto Zoo Functions

Foi utilizada a linguagem de programação Javascript.

O objetivo do projeto foi consolidar o conhecimento no uso de High Order Functions no Javascript, utilizando os métodos forEach, filter, some, find, 
every, map, e reduce, criando um sistema de gerenciamento de um zóologico.

Foram criadas funções no arquivo src/zoo.js de acordo com os requisitos pedidos.

O projeto não foi refatorado após sua entrega (09/06/2021).
***
Os requisitos que compõem projeto são:

:white_check_mark: Implementar a função getSpeciesByIds que retorna um array contendo as espécies referentes aos ids passados como parâmetro, 
podendo receber um ou mais ids;

:white_check_mark: Implementar a função getAnimalsOlderThan que retorna um valor booleano caso os animais atendam ao requisito a partir do nome de uma espécie e 
uma idade mínima;

:white_check_mark: Implementar a função getEmployeeByName que faz uma busca das pessoas colaboradoras através do primeiro ou do último nome delas;

:white_check_mark: Implementar a função createEmployee que cria um objeto equivalente ao de uma pessoa colaboradora a partir de informações recebidas nos parâmetros;

:white_check_mark: Implementar a função isManager que retorna um valor booleano após a verifição se uma pessoa colaboradora, a partir de seu id, 
ocupa cargo de gerência;

:white_check_mark: Implementar a função addEmployee que adiciona um novo funcionário ao array employees no arquivo scr/data.js;

:white_check_mark: Implementar a função countAnimals que retorna a quantidade de animais de acordo com a espécie inserida;

:white_check_mark: Implementar a função calculateEntry que calcula o valor total de entradas a partir da quantidade de entradas de Adult, Child e Senior;

:white_check_mark: Implementar a função getAnimalMap que retorna a localização dos animais no zoológico de acordo com os parâmetros inseridos, podendo retornar 
com os nomes, de acordo com sexo, em ordem alfabética ou todos os animais;

:white_check_mark: Implementar a função getSchedule que retorna o horário de funcionamento do zoológico;

:white_check_mark: Implementar a função getOldestFromFirstSpecies que retorna o animal mais da primeira espécie cuidada por um funcionário, de acordo com o 
id fornecido;

:white_check_mark: Implementar a função increasePrices que altera o valor das entradas em src/data.js de acordo com o porcentual inserido;

:white_check_mark: Implementar a função getEmployeeCoverage que identifica as espécies pelas quais um funcionário é responsável, através de seu nome, último nome
ou id;
