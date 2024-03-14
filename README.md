
# FORMATAÇÃO DE REGISTRO DEV FRIENDLY

Esse repositório tem como finalidade aproximar o doc [M001](https://docs.zanthusonline.com.br/wp-content/uploads/2024/02/M001-Formatacao-de-Registros.pdf) de formatação de registros zanthus para analistas aos desenvolvedores PHP. 

Sinta-se à vontade para adicionar mais arquivos nesse documento! 


## FAQ

#### O que é o jetbrains toolbox? 

Pra esse documento, é como vc faz pra acessar o lugar exato descrito na seção do arquivo. Você pode encontrar mais informações no link
[toolbox](https://www.jetbrains.com/toolbox-app/)

#### Como acesso os links?
Copia e cola no browser que ele te leva ao arquivo e à linha. 


##  Arquivo 22: Produtos/Departamentos vinculados a Promoções

#### Onde encontrar?
classes/class_promocao.inc 

#### link toolbox: 

```javascript
jetbrains://php-storm/navigate/reference?project=manager&path=classes/class_novapromocao.inc:2802
``` 

#### Como funciona?

É criado um loop do tipo 0 ao 12 (campo A22ACA). Para cada um dos tipos, é criado um sistema de ifelse que verifica qual o tipo da vez e altera a query SQL e então essa query SQL contendo os dados é executada e posteriormente processada num while.

Entre a execução da query e o processamento dos registros, tem alguns ifs com configs específicas por tipo de arquivo. 

Na linha 3216

```javascript
jetbrains://php-storm/navigate/reference?project=manager&path=classes/class_novapromocao.inc:3216
``` 

São geradas as linhas que serão concatenadas num array de linhas que será enviado para o kernz_envia_sdf. 

A tabela do arquivo 22 pode ser comparada com o esquema criado em ImportaSDF22():

```javascript
jetbrains://php-storm/navigate/reference?project=manager&path=classes/class_novapromocao.inc:3435
``` 
Pois as informações de Início e Tam estão iguais. 
