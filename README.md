# Eventos App
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/MichaelCX77/eventosapp/blob/master/LICENSE)

<br/>
O Eventos App é uma aplicação desenvolvida para o registro e controle de eventos e convidados.
<br/>

## <li> Sobre o Projeto

Clique <a href="https://eventoapp2019.herokuapp.com/">aqui</a> e acesse a aplicação em núvem<br/>

<br/>
    
<b><i>Observação: O Eventos App foi desenvolvida como objeto de estudo, quando eu estava aprendendo a programar com SpringBoot e Thymeleaf</i></b>
    
<br/>

## <li> Layout da Plataforma

<br/>
<div align="center">
    <img width="1000em" src="https://github.com/MichaelCX77/assets/blob/master/assets-eventosapp/png/cadastro_evento.png"></a><br/><br/>
    <img width="1000em" src="https://github.com/MichaelCX77/assets/blob/master/assets-eventosapp/png/detalhe_evento.png"></a><br/><br/>
    <img width="1000em" src="https://github.com/MichaelCX77/assets/blob/master/assets-eventosapp/png/lista_eventos.png"></a><br/><br/>
</div>
<br/>

# Tecnologias utilizadas


## Front end

<li> HTML
<li> CSS
<li> Thymeleaf

  
<br/>
  
## Back end
  
<li> Java / SpringBoot
<li> Maven
<li> Outras Biblitecas e Ferramentas: Crud Repository, JPA, ModelAndView.

<br/>
  
## Implantação em Produção

<li> Hospedagem da aplicação em Núvem Heroku
<li> Banco de dados Postgresql em Nuvem Heroku (AWS)
  
<br/><br/>
  
# Como criar o banco de dados local
    
  Pré Requisitos: PSQL com variáveis de ambiente configuradas
    
 ```bash
  #1 Logar no console PSQL
    Logar em uma database do PSQL (PostgreSQL) com usuário que possua permissões de administrador
  
  #2 Executar script de criação do banco
    Executar script "Criação do Banco Local.sql" presente na pasta "doc" do projeto
  ```
<br/>   
   
# Como executar o Projeto

Pré Requisito: Java 8 e Maven com variáveis de ambiente configuradas

  ```bash
#1 clonar repositório
  git clone https://github.com/MichaelCX77/eventosapp
  
#2 entrar na pasta do projeto
  cd eventosapp
 
#3 executar build maven
  mvn clean package
    
#4 executar artefato
  java -jar target/eventoapp-{VERSION}.jar
    
  ```
  
  
  
  
  
