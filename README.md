# Challenge de Data Science

<div align="center">
<img src="https://i.imgur.com/oxab3uu.png" width="800px" />
</div>

Fazemos parte de uma equipe de dados que foi contratada para fazer parte do banco digital internacional chamado **Alura Cash**. Logo no primeiro dia fomos convocados pela diretoria financeira para uma reunião, a qual nos informou que, recorrentemente, estão surgindo pessoas inadimplentes após a liberação de créditos.

Por conta disso, foi solicitada uma solução para para diminuir as perdas financeiras geradas por conta de pessoas mutuarias que não quitam suas dívidas. Nos foi informado também que teríamos **um mês** para encontrar essa solução e apresentá-la à diretoria financeira. Sendo assim, solicitamos um conjunto de dados que contenha as informações de clientes, da solicitação de empréstimo, do histórico de crédito, bem como se a pessoa mutuaria é inadimplente ou não.

Após a reunião, nossa equipe se reuniu e concordamos em dividir nossos trabalhor por semanas, de forma que, na 1° semana trabalharíamos com os dados em SQL utilizando o MySQL, na 2° semana construiríamos um modelo de Machine Learning (ML) que classificaria os clientes em possíveis inadimplentes ou não. Por fim, na 3° e 4° semanas iríamos desenvolver nosso protifólio em Power BI, mostrando tudo que encontramos nas semanas 1 e 2 para podermos mostrar os resultados para a diretoria.

## Semana 1

A semana 1 é dedicada a análise e estruturação dos dados oferecidos pelo banco com MySQL. Primeiro, foi notado que os dados estavam diferentes dos usuais, pois sua fonte era um ***dump***, o que nos exigiu uma atenção especial na manipulação deles. Portanto, buscamos ler todo o registro para entender nossos dados. Notamos então que os valores estavam divididos por tabelas características, com valores de ID referenciando os dados de cada cliente.

Então, iniciamos analisando as informações que o conjunto de dados possuia. Assim, foi notado que nossos dados estavam em inglês, os valores de texto estavam sem padronização, além de vários valores nulos.

Foi percebida também a existencia de uma tabela que continha a relação de todos os IDs de uma mesma pessoa cliente do Alura Cash. Dessa forma o primeiro passo foi tratar nossos dados para deixá-los padronizados no texto, bem como, corrigir inconsistências relacionadas ao tipo e estruturação dos dados.

Depois buscamos unir as tabelas pelos valores de IDs que eram correspondentes entre si deixando todos os dados em uma única tabela de dados dos clientes. Além disso, após uma conversa entre a equipe decidimos não eliminar os valores nulos dentro do banco de dados, pois poderiam conter informações de clientes que são importantes para o banco.

A tabela de dados unidos foi exportada do MySQL como ***csv*** e será a tabela de dados utilizada nas próximas semanas.
## Equipe de dados

### Maria Gabriela

<div align="left">
<img src="https://i.imgur.com/z7wOCI9.png" width="300px" />
</div>

Maria é formada em Sistemas para Internet, apaixonada por tecnologia, dados e gatos. Atuou na área de infra e desenvolvimento. Atualmente é especialista em SQL, com conhecimento nos bancos de dados mais utilizados atualmente e um pézinho em BI, onde tem se desenvolvido tecnicamente.

<a href="https://www.linkedin.com/in/mariagcoliva/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>

### Danielle Oliveira

<div align="left">
<img src="https://i.imgur.com/JBep2hL.png" width="300px" />
</div>

Danielle é formada em Sistemas de Informação. Fez parte do Scuba Team. Atualmente é instrutora nas áreas de Banco de dados, Business Intelligence e NoSQL. É apaixonada por livros, música e tecnologia.

<a href="https://www.linkedin.com/in/danielle-oliveira-071550134/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>

### Mirla Costa

<div align="left">
<img src="https://i.imgur.com/eqC6qrV.jpg" width="300px" />
</div>

Graduanda em Engenharia elétrica pela Universidade Federal do Piauí com pesquisa focada em Aprendizado de Máquina e Inteligência Computacional. Atuo como Scuba na escola de Data Science da Alura sempre amei muito programar, ensinar de trabalhar com tecnologia. Meu tempo livre dedico a brincar com meus animias, assistir animações e séries, além de jogar RPG de mesa.

<a href="https://www.linkedin.com/in/mirla-costa/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
</div>

### João Miranda

<div align="left">
<img src="https://i.imgur.com/6evW05p.png" width="300px" />
</div>

Bacharel em Matemática pela UFMG e especialista em Data Science e Analytics pela USP/Esalq. Atualmente sou instrutor na Escola de Dados do grupo Alura. Gosta muito de livros, jogos eletrônicos, boardgames e tiro com arco.

<a href="https://www.linkedin.com/in/joaovmiranda/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
