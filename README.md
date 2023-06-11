# Lambda Coversor de Temperatura
<h1 align="center">Article Model</h1>
<p align="center"><i>Repositório para versionamento e documentação do projeto utilizado durante a série de artigos no GitHub.</i></p>

<p align="center"><i>Aluno: Guilherme de Oliveira Souza RA: 1006</i></p>

<p align="center"><i>Link da AWS: https://us-east-1.console.aws.amazon.com/lambda/home?region=us-east-1#/functions/InversorTemperatura?tab=code</i></p>

##  Conversor de Temperaturas de Celsius para Fahrenheit
Uma função Lambda para converter uma lista de temperaturas de Celsius para Fahrenheit.

##  Funcionalidades
A função Lambda é capaz de:

Receber uma lista de temperaturas em Celsius.
Converter cada temperatura para Fahrenheit.
Retornar a lista de temperaturas convertidas.
Uso
A função Lambda pode ser invocada enviando um evento com a seguinte estrutura:

## json
```
{
  "temperatures": [25, 30, 15, 10]
}
```
As temperaturas devem ser fornecidas em graus Celsius.

###  Dependências
A função Lambda não possui dependências externas. Ela utiliza apenas as bibliotecas padrão do Python.

##  Instruções para Execução
Para executar a função Lambda:

Crie uma função Lambda no provedor de cloud escolhido.
Faça o upload do código fonte (lambda_function.py) para a função Lambda.
Configure a função Lambda para invocar a função lambda_handler no arquivo lambda_function.py como o ponto de entrada.
Defina as permissões necessárias para a função Lambda acessar outros serviços, se necessário.
Salve as configurações e teste a função Lambda.

### Teste
Você pode testar a função Lambda utilizando o Console de Gerenciamento do provedor de cloud escolhido ou invocando a função através de um evento programático.

Ao fornecer a lista de temperaturas em Celsius, a função Lambda retornará a lista de temperaturas convertidas em Fahrenheit.

###  Considerações de Segurança
Certifique-se de que a função Lambda esteja configurada para executar com as permissões apropriadas.

Verifique se o código fonte está livre de vulnerabilidades conhecidas e siga as boas práticas de segurança ao configurar a função Lambda.

### Technologies
<p display="inline-block">
  <img width="48" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Amazon_Web_Services_Logo.svg/640px-Amazon_Web_Services_Logo.svg.png" alt="aws-logo"/></p>
</p>
                                                                                                  
### Development Tools

<p display="inline-block">
  <img width="48" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png" alt="vscode-logo"/>
  <img width="48" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Amazon_Web_Services_Logo.svg/640px-Amazon_Web_Services_Logo.svg.png" alt="aws-logo"/></p>
