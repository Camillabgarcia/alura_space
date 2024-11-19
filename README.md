**Curso de Django: Templates e Boas Práticas**

Este repositório contém o resultado das práticas realizadas por mim durante o curso Django: Templates e Boas Práticas, onde explorei o desenvolvimento de aplicações web utilizando o framework Django.

🚀 **Tecnologias Utilizadas**

Python

Django 4

Virtualenv

Jinja2

📚 O que foi aprendido

**Introdução ao Django**

Compreendi a história e os principais aspectos do Django 4.

Configurei um ambiente virtual com virtualenv para isolar as dependências do projeto.

Criei o projeto com o comando django-admin startproject setup.

Executei o servidor de desenvolvimento pela primeira vez com o comando python manage.py runserver.

**Configurações Iniciais**

Realizei alterações no arquivo settings.py, como a timezone e o idioma padrão.

Aumentei a segurança do projeto, protegendo a SECRET_KEY e utilizando o pacote python-dotenv para armazenar variáveis de ambiente em um arquivo .env.

Subi o projeto para um repositório remoto no GitHub, configurando um arquivo .gitignore para proteger dados sensíveis.

**Estrutura do Projeto**

Compreendi a diferença entre projetos e apps no Django.

Criei uma app chamada galeria utilizando o comando python manage.py startapp galeria.

Desenvolvi minha primeira página personalizada configurando rotas em views.py e urls.py.

Segui a boa prática de criar um arquivo urls.py para cada app.

**Trabalhando com Templates**

Isolei os templates da app galeria em uma pasta dedicada chamada templates.

Reconfigurei o settings.py para utilizar os templates isolados.

Organizei melhor os arquivos estáticos, criando subpastas dentro de templates para cada app.

**Boas Práticas com Templates** 

Implementei um novo template HTML personalizado com arquivos estáticos para melhorar a aparência do site.

Apliquei a prática DRY (Don't Repeat Yourself) criando um template base chamado base.html para reutilizar trechos de código comum.

Utilize o conceito de Partials para dividir o código em partes menores, tornando o site mais escalável e o desenvolvimento mais eficiente.

🌟 **Conclusão**

Este projeto destaca boas práticas e o uso eficiente de templates no Django, aplicando conceitos importantes como DRY e Partials para criar aplicações escaláveis e organizadas.

