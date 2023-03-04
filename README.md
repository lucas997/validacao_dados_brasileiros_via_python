# Validacao de dados brasileiros via python

Este repositório foi feito para fins acadêmicos onde mostra um projeto feito com a línguagem python. O intuíto desse projeto é verificar validações de dados no formato brasileiro, neste cenário foram criadas classes robustas que cumprem com requisitos e funcionalidades que a empresa fictícia ByteBank solicitou. os pontos principais de cada classe são:

* Validação e retorno de CPF's e CNPJ's utilizando uma boa prática de programação chamada factory, que nada mais é do que uma classe que retorna outras classes de acordo com algum atributo em comum. 

* Formatação de telefones brasileiros utilizando regex: o regex é outra forma de validação onde valida e formata o tipo de dado, neste caso em específico foram os números de telefones

* Validação de datas: utilizando as principais bibliotecas do python que se usa neste treinamento, foi usada a biblioteca do python para criar os próprios métodos que retornem de maneira mais agradável para o usuário brasileiro. Uma informação como mês por exemplo, que retorne o mês do ano no idioma PT-BR. Este mesmo método também foi feito para os dias da semana e também foi feita a formatação de datas para o formato brasileiro, seguindo a ordem adotada para o país(dia, mês e ano).

* Validação de CEP: a classe "BuscaEndereco" ela valida e formata um CEP e o diferencial dessa classe é que foi necessário acessar uma API através do python, usando a biblioteca requests, onde foi coletada as informações do servidor e conseguiu exibir para o usuário.
