# AWS Elastic Beanstalk - Exemplo de contato 
Esta aplicação de exemplo utiliza o [Express](https://expressjs.com/) framework e [Bootstrap](http://getbootstrap.com/) para construir uma forma simples e escalável cliente de inscrição que é implantado no [AWS Elastic Beanstalk](http://aws.amazon.com/elasticbeanstalk/). A aplicação armazena dados em [Amazon DynamoDB](http://aws.amazon.com/dynamodb/) e publica as notificações à [Amazon Simple Notification Service (SNS)](http://aws.amazon.com/sns/) quando um cliente preenche o formulário, neste momento é enviada uma mensagem para a fila SNS que envia o email para o subscriber default.

## Features
### Themes
O código inclui vários temas de Bootstrap [bootswatch.com](http://bootswatch.com/). Você pode alterar dinamicamente o tema ativo, configurando a variável de ambiente TEMA na [Elastic Beanstalk Management Console](https://console.aws.amazon.com/elasticbeanstalk):

![](misc/theme-flow.png)

Temas instalados incluem:

* [amelia](http://bootswatch.com/amelia)
* [default](http://bootswatch.com/default)
* [flatly](http://bootswatch.com/flatly)
* [slate](http://bootswatch.com/slate)
* [united](http://bootswatch.com/united)

para ver o [Site](http://www.devhernand.com/) 