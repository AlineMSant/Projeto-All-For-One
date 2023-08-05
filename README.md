# All For One

## Descrição
Neste projeto, tive a oportunidade de praticar todos os conceitos de SQL utilizando o banco de dados Northwind.


## Configurações do projeto
Antes de começar, verifique se você possui o Docker Compose na versão 1.29 ou superior instalado. Caso contrário, consulte a documentação para realizar a instalação.

Para iniciar o projeto utilizando o Docker, siga as orientações abaixo:

1. Execute o comando para iniciar os serviços node e db utilizando o Docker Compose:
```bash
docker-compose up -d
```
2. Verifique se o serviço MySQL local, caso esteja em execução na porta padrão (3306), foi parado. Caso contrário, adapte as configurações de porta para evitar conflitos com os containers.

## Utilização do Container
Após iniciar o ambiente com o Docker Compose, você pode executar os seguintes comandos:

- Para acessar o terminal interativo do container all_for_one, execute o comando:
```bash
docker exec -it all_for_one bash
```

- Dentro do terminal do container, você pode instalar as dependências específicas do projeto com o comando:
```bash
npm install
```

- Importante: Todos os comandos definidos no arquivo package.json (como npm start, npm test, npm run dev, etc.) devem ser executados dentro do container. Certifique-se de utilizar o terminal do container para executar esses comandos.

## Clonando o Respositório
Para clonar o repositório e iniciar o projeto, execute os seguintes passos:

1. Clone o repositório

2. Acesse o diretório do projeto:
```bash
cd all-for-one
```
3. Instale as dependências:
```bash
npm install
```

## Habilidades desenvolvidas:
- Utilização de SQL para consultas e manipulação de dados em um banco de dados.
- Uso do Docker e Docker Compose para configurar e executar o ambiente do projeto.
- Prática de consultas complexas utilizando a base de dados Northwind.

## Formas de contato:
Email: alinems4120@gmail.com <br>
Linkedin: <a href="https://www.linkedin.com/in/alinemourasantos-dev/" target="_blank">Clique aqui</a>
