# eventex-2.0
Criação do projeto para divulgação de inscrições, email de confirmação e pagamento, desenvolvido no curso WTDD
## Ferramentas
* python na versão 3.7
* Django na versão 2.1
* Virtualenv para criar ambientes virtuais
* Sublime Text como editor de código
## Configuração Inicial

* Ter o python 3.7 instalado no seu sistema operacional
O meu por ser uma distribuição Linux foi bem simples executei os comandos abaixo:  

`` apt-get install pyton3 ``  
`` pip3 install virtualenv ``  
* Criar um ambiente virtual para isolar as dependências do projeto:  
1. Crie um diretório com o nome que achar melhor, o meu foi __wtdd__.  
* Agora vamos criar nosso ambiente virtual com o comando:  
`` virtualenv .wttd -p python3 `` isso para mim foi necessário pois tenho o python2 instalado  
__.wtdd__ é nome do meu ambiente virtual e o ponto é para deixa-lo oculto.  

* Dentro da raiz do diretório __wtdd__ execute o seguinte comando:  
`` source .wtdd/bin/activate ``  
Verá uma linha parecida com isso:``  (.wtdd) user-name-system:~/SeuDiretório/wttd$ ``  
Pronto com seu ambiente virtual ativado vamos instalar o django.  
`` pip install django ``  
Pronto agora vamos criar nosso projeto __Django__.  
### Criando um projeto Django  
Com o nosso ambiente virtual ativado, digite o comando:  
`` django-admin startproject eventex . ``  
verá que no seu diretório __wtdd__ terá uma pasta __eventex__.  
Depois só digitar: `` python manage.py runserver `` e vai poder acessar seu projeto em:  
`` http://127.0.0.1:8000/ ``.
