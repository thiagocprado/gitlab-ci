O que é o git lab?
o que é pipeline?
o que é CI e CD?
o que é SCM?
o que é S3
o que é o Docusaurus.io
o que é o surge.sh
o que é um gitlab runner?
o que é um bullet?
trunk based
crawler

primeiro passo é criar o arquivo gitlab-ci.yml

-- Docusaurs -> Basicamente cria um site base para podermos customiza-lo

-- Surge -> Permite que disponibilizemos nosso site em um servidor remoto 

surge login - para logar
surge logout - para deslogar

surge - para publicar o site

surge teardown - para remover o projeto

surge --project build/missaodevops/
surge --project build/missaodevops/ --domain thiago.surge.sh


-- Broken Link Checker -> verifica se todos os links que possuimos no projeto são funcionais 

blc --recursive --exclude-external <url>

-- Snyk -> faz testes de vulnerabilidades