# Aprendizagem por Projetos Integrados - BANCO DIGITAL

## FATEC -  Profº Jessen Vidal, SJC - 1º Semestre DSM - 2022/2

<hr>

<p align="center">
      <img src="./src/static/images/01-logo_octoplus_bank_transparente.png" alt="logo da equipe" width="200">
      <h3 align="center">🐙 Octoplus Holding 🐙</h3>

<hr>

<p align="center">
<a href="#API">Aprendizagem por Projetos Integrados</a> •
 <a href="#sobre">Sobre</a> •
 <a href="#tecnologias">Tecnologias utilizadas</a> •
 <a href="#comousar">Como Utilizar</a> • 
 <a href="#demonstracao">Demonstração</a> • 
 <a href="#userstories">User Stories</a> • 
 <a href="#backlogs">Backlog da Sprint</a> •
 <a href="#burndown">Burndown da Sprint</a> •
 <a href="#equipe">Equipe</a> • 
</p>
<hr>

## Aprendizagem por Projetos Integrados <a id="API"></a>
A API (Aprendizagem por Projetos Integrados), desenvolvida no escopo do CADI, é a metodologia de ensino em implantação na Fatec São José dos Campos, desde o Segundo Semestre de 2019, do qual os alunos formam equipes baseadas na metodologia scrum, tendo um aluno como master, Product Owner e os integrates restantes dev team. O time é desafiado por um cliente real (nesse projeto nosso cliente é a MidAll: Tecnologias), a desenvolver uma solução para um problema, tendo que atender requisitos exigidos de tecnologia. <br> 
  
  O API segue tendo como pilares os seguintes valores: <br>
 - Real Problem Based Learning (rPBL) <br>
 - Validação Externa <br>
 - Mindset Ágil (Agile) <br>

<hr>

## Sobre o Projeto <a id="sobre"></a>

O tema a ser abordado neste API é o desenvolvimento de um sistema para um Internet Banking; monitorando e controlando operações bancárias e reduzindo a necessidade de interações presenciais.
<br>
<br>

> Baseado na Metodologia Ágil - Scrum
<br>

_Projeto de um banco fictício, representado pelo Profº Fabrício Galende Marques de Carvalho._

<br>
<hr>

## 💻 Tecnologias Utilizadas <a id="tecnologias"></a>
<br>

![tecnologias3ASPRINT](https://user-images.githubusercontent.com/111464795/200388764-10711847-228a-467a-a6cf-f1e6fc971066.png)

<br>
<hr>


## 📄 User Stories <a id="userstories"></a>


| Código (US) | Quem       | O que?                                                                                                                                                   | Para                                                |
| :----: | :--------- | :------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------- |
|  #01 à #05    | Cliente | Gostaria de solicitar abertura de uma ou mais contas, bem como excluí-las, fazer alterações e realizar transações básicas como saque e depósito.                     | Para me cadastrar no sistema e realizar transações financeiras.
|  #06 à #12   | Gerente de Agência | Gostaria de ter as mesmas atribuições de um cliente, bem como gerenciar as contas dos clientes com minhas devidas funções (cornfirmações de cadastros, alterações de dados cadastrais, exclusão de contas e confirmações de depósitos)                     | Para realizar funções administrativas da agência. 
|  #13 à #16   | Banco | Gostaria de entrar com o capital, bem como aumentar e diminuir o montante total | Para disponibilizar empréstimos aos clientes.
|  #17 à #21   | Gerente Geral | Gostaria de ter as mesmas atribuições de um gerente de agência, bem como exercer funções administrativas relacionadas a aberturas de agências e possíveis alterações das mesmas. | Para realizar funções administrativas do banco.
|  #22   | Cliente | Gostaria de movimentar valores entres contas da mesma ou de diferentes agências| Para realizar transferências de valores entre contas.

<br>
<hr>

## ❓Como Utilizar <a id="comousar"></a>
<br>

<h3>Possuir os seguintes aplicativos em sua máquina:</h3>

> Python 3.10 - https://www.python.org/ <br>
> Wamp Server 3.2.6 - https://www.wampserver.com/en/ <br>
> MySQL Workbench 8.0.30 - https://dev.mysql.com/downloads/workbench/ <br>

<h3>Clonar o repositório</h3>

> https://github.com/OctoplusHolding/OctoplusBank.git

<h3>Abrir o CMD na pasta OctoplusBank e digitar:</h3>

```python
	python -m venv venv
```

```python
	venv\Scripts\Activate.ps1
```

<h3>Instalar os pré-requisitos digitando:</h3>

```python
	pip install -r requirements.txt
```

<h3>Importar a base de dados mais recente que se encontra em Modelagem de Banco de Dados para o seu SGBD(Preferencialmente Mysql + Wamp)</h3>

<h3>Fazer as alterações (root/senha) no arquivo db.sql de acordo com o root e a senha do seu SGBD</h3>

<h3>Executar:</h3>

```python
	py main.py
```

<h3>Abrir o site em: 'http://localhost:4000/'</h3>

<br>
<hr>


## 💡Demonstração do programa <a id="demonstracao"></a>
<br>
<h3> Sprint 01 </h3>

![gifSprint1](https://user-images.githubusercontent.com/111452998/191324088-233ba443-30fc-443a-93ec-c2ff57b2d3ac.gif)
<br>

<h3> Sprint 02 </h3>

<img src="./src/static/images/sprint2.gif" alt="gif 2a sprint">
<br>
<hr>

<h3> Sprint 03 </h3>

<img src="./src/static/images/3a_sprint_GG_GA_transferencia.gif" alt="gif 3a sprint">
<br>
<hr>
## 🗂️ Backlog das Sprints <a id="backlogs"></a>
<br>

![backlog02](https://user-images.githubusercontent.com/111464795/194782244-0cf68435-ea58-4e18-aee5-69eec329923e.png)


<br>
<hr>

## 📉 Burndown das Sprints <a id="burndown"></a>

<br>

<h3> Sprint 1: [29/08/22-18/09/22]</h3> 

![burndown1](https://user-images.githubusercontent.com/111464795/194780059-45f718b3-3247-45cd-bcd9-4ed35872ba60.png)

<br>
<br>

<h3> Sprint 2: [19/09/22-09/10/22]</h3> 

![burndown2](https://user-images.githubusercontent.com/111464795/194780063-b9e62317-fc5a-464e-8b63-6c2d21e1eeb3.png)

<br>
<br>

<h3> Sprint 3: [17/10/22-06/11/22]</h3> 

![burndown3](https://user-images.githubusercontent.com/111464795/200386558-965e69de-eaf0-46a0-8598-450adff7aaeb.png)

<br>
<br>

<h3> Sprint 4: [07/11/22-27/11/22]</h3> 

<br>
<br>

<hr>

## :mortar_board: Equipe <a id="equipe"></a>

| Membro                | Função        | Github                                                                                                                                                | Linkedin                                                                                                                                                                                         |
| :-------------------: | :-----------: | :---------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | 
| Gabriel Briscese         | Scrum Master  | <a href="https://github.com/Briscese"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>   | <a href="https://www.linkedin.com/in/gabriel-brosig-briscese-344a5587/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">                                  |
| Thiago Zani         | Product Owner | <a href="https://github.com/zani19"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/thiago-zani-1b8503249"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                |
| Gabriela Barbosa       | Desenvolvedora | <a href="https://github.com/gabidsbarbosa"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>     | <a href="https://www.linkedin.com/in/gabriela-barbosa-51a095195"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                              |
| Igor Sasaki          | Desenvolvedor | <a href="https://github.com/IgorKenzoMS"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>   | <a href="https://www.linkedin.com/in/igor-kenzo-miyazaki-sasaki-4782b5249"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                      |
| Jean Faria       | Desenvolvedor | <a href="https://github.com/jeejinf"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/jean-faria-5a4b201b9/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> 