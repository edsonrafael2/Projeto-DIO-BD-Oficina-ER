# Projeto-DIO-BD-Oficina-ER


Esquema conceitual de um banco de dados


Uma Oficina



* Sistema de controle e gerenciamento de execuções de ordens de serviços em uma oficina mecanica

* Cliente levam veiculos a oficina mecanica para serem consetados oi para passarem por revisões periodicas

* Cada veiculo é designado a uma equipe de mecanicos que identifica os serviços a serem executados e preenche uma OS com a data de entrega

* A partir da OS calcula-se o valor de cada serviço consultando-se uma tabela de referencia de mao de obra

* O valor de cada peça tambem ira compor a OS

* O cliwnte autoriza a execução dos serviços

* A mesm equipe avalia e executa os serviços

* Os mecanicos possuem codigo nome endereço e espeialidade

* Cada OS possui numero, data de emissão, um valor, status, e uma data para conclusão dos trabalhos

* Uma OS pode ser composta por varios serviços e um mesmo serviço pode estar contido em mais de uma OS

* Uma OS pode ter varios tipos de peça e uma peça pode estar presente em mais de uma OS.
