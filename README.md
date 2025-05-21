"# Tema-Docker-Git-GitHub-Hospedagem-de-P-gina-com-Nginx" 

o	Objetivo do projeto.
        Realizar atividade de Docker

o	Comandos utilizados.
        git init
        git add README.md
        git branch -M main
        git remote add origin https://github.com/Evandro-ESD/Tema-Docker-Git-GitHub-Hospedagem-de-P-gina-com-Nginx.git
        git add .
        git commit -m "Hospedagem de Página com Nginx"
        git push -u origin main


o	Como executar o container.
        docker build -t atividade-pontuacao .   
        docker run -d --name atividade-pontuacao -p 8080:80 atividade-pontuacao  