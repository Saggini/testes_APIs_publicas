# Estudos de automacao de APIs púplicas

### Linha de comando ####
**************
Para baixar as bibliotecas utilize o seguinte comando:
> pip install -r requirements.txt
**************
Para rodar todos os cenários de testes automatizados utilizar o seguinte comando:
>robot -d ./Result API\tests
**************
Para rodar apenas um cenário utilizamos a tag como referência, utilizamos o seguinte comando:
> robot -d ./Result  -i nomedatag  API/tests
*************
Para não rodar algum cenário específico no regressivo é utilizado o seguinte comando:
> robot -d ./Result -e nomedatag API/tests

#### Links de consulta ####

+ [Python](https://www.python.org/downloads/)
+ [Gorest](https://gorest.co.in/)
+ [Códigos de retorno](https://desenvolvedores.skyhub.com.br/guias-api-skyhub/codigos-de-retorno-http-status)
+ [Schema](https://www.jsonschema.net/login)

### Links das Librarys RobotFramework ###
+ [RequestLibrary](http://marketsquare.github.io/robotframework-requests/doc/RequestsLibrary.html#DELETE)
+ [BuiltIn](https://robotframework.org/robotframework/latest/libraries/BuiltIn.html)

### TAGS ####
--------------------------------------------------------------------
| tag > Descrição

> -i | Serve para indicar qual cenario vai serexecutado pela tag
********************************************************************
> -e | Serve para indicar qual teste não irar rodar pela tag
********************************************************************
> -v | Serve para setar o valor de uma variavel na hora da execução
********************************************************************
> -d | Serve para indicar qual pasta a evidencia ficara salva