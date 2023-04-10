<p align="center">
  <a href="https://medium.com/@renan_gs/usando-web-scraping-para-coletar-sequências-de-dna-f7e96150d092">
    <img width="600" src="https://i.imgur.com/6zM7JBq.png">
  </a>
</p>
<p align="center">
  <img  src="https://img.shields.io/github/license/renan-almeidaa/moveit" alt="License">

  <img src="https://img.shields.io/github/forks/renan-almeidaa/moveit" alt="Forks">     

  <img src="https://img.shields.io/github/stars/renan-almeidaa/moveit" alt="Stars">
</p>

## 💻 Sobre o projeto

  Estava desenvolvendo meu TCC e precisava fazer uma mineração em sequências de inserção em DNAs utilizando o algoritmo de ECLAT para o reconhecimento de padrões frequentes. Porém, eu só possuia 16 amostras que foram coletadas manualmente por meio do site tncentral, sendo uma quantidade pequena para realizar a mineração. 
  
  Pesquisando um pouco, descobri uma base de dados disponilizada no github (fonte: https://github.com/thanhleviet/ISfinder-sequences ). Nele contém um arquivo csv que possui mais de 6000 sequências de DNA contendo informações como nome, família, grupo, entre outros. No arquivo também é disponibilizado o link que leva para o site do isfinder onde é possível ter acesso á sequência.
  
  
  Dessa forma, foi possível realizar a extração de 307 sequências de DNA e páginas HTML de forma automatizadad com Web Scrapping.
  
## 🚀 Tecnologias

This project was developed using the following technologies:

- [Beautiful Soup](https://pypi.org/project/beautifulsoup4/)
- [Requests](https://pypi.org/project/requests/)
- [Pandas](https://pandas.pydata.org)
- [Jupyter Notebook](https://jupyter.org)

## 📎 Mais informações

- Para mais detalhes sobre esse projeto, acesse o meu artigo no medium -> [bit.ly/3GqGvM5](http://bit.ly/3GqGvM5)

- Para mais detalhes sobre a mineração de dados aplicada nessa base de dados para reconhecimento de padrões frequentes em sequências de inserção da família IS4 com o algoritmo de ECLAT e k-mers -> [bit.ly/3zFmDkI  ](https://bit.ly/3zFmDkI)
