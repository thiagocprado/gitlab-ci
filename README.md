- O que é o Gitlab?
  . É uma plataforma de hospedagem de código-fonte.
  
  . Permitem que desenvolvedores contribuam em projetos privados ou abertos (open source).
  
  . Os projetos são denominados respositório.
  
  . O Gitlab proporciona, nativamente, ferramentas de integração e entrega contínua, além de outras ferramentas.
  
-------------------------------------------------------------------------------------------------------------------------------

- O que é pipeline?
  . Uma pipeline basicamente é onde os processos acontecem.
  
  . Uma pipeline é um grupo de jobs que são executados em estágios. 
  
  . Todos os jobs em um estágio são executados em paralelo (se houver Runners suficientes), e se todos eles tiverem sucesso, 
  a pipeline move para o próximo estágio. 
  
  . Se um dos jobs falharem, o próximo estágio não será executado (geralmente).

-------------------------------------------------------------------------------------------------------------------------------

- O que é Continuos Integration / Integração Contínua? 
  . Um serviço de integração contínua cria e executa automaticamente testes de unidade nas novas alterações de código para destacar 
  imediatamente todos os erros.
 
  . Geralmente, a integração contínua se refere ao estágio de criação ou integração do processo de lançamento de software, 
  além de originar um componente de automação e um componente cultural. 
  
  . Os principais objetivos da integração contínua são encontrar e investigar bugs mais rapidamente,
  melhorar a qualidade do software e reduzir o tempo que leva para validar e lançar novas atualizações de software.
 
  . A integração contínua ajuda sua equipe a ser mais produtiva ao liberar os desenvolvedores de tarefas manuais e encorajar 
  comportamentos que ajudam a reduzir o número de erros e bugs implantados para os clientes.
 
  . Com testes mais frequentes, sua equipe pode descobrir e investigar bugs mais cedo, antes que no futuro os 
  problemas cresçam demais.
  
  . A integração contínua ajuda a sua equipe a distribuir atualizações para os clientes mais rapidamente e com maior frequência.

-----------------------------------------------------------------------------------------------------------------------------------

- O que é Continuos Delievery / Distribuição Contínua?
  . As alterações de código são automaticamente preparadas para uma liberação para teste ou produção.
  
  . Com a distribuição contínua, cada alteração de código é criada, testada e enviada para um ambiente de teste 
  ou preparação, que não pertence à produção.

  . É possível que existam vários estágios de teste paralelos antes de uma ordem de produção ser implantada.

  . A diferença entre entrega contínua e implantação contínua é a presença de uma aprovação manual 
  para atualizar o ambiente de produção.

  . A distribuição contínua permite que a sua equipe crie, teste e prepare automaticamente alterações de código para liberar 
  a produção, de modo que a distribuição de software seja mais rápida e eficiente.

  . Estas práticas ajudam sua equipe a ser mais produtiva ao liberar os desenvolvedores de tarefas manuais e encorajar 
  comportamentos que ajudam a reduzir o número de erros e bugs implantados que chegam aos clientes.

  . Com testes mais frequentes e abrangentes, sua equipe pode descobrir e investigar bugs mais cedo, antes que no futuro 
  os problemas cresçam demais. A distribuição contínua permite que você execute tipos de teste adicionais no seu código, 
  pois o processo completo já foi automatizado.

  . A distribuição contínua ajuda a sua equipe a distribuir atualizações para os clientes mais rapidamente e com maior 
  frequência. Quando a distribuição contínua for implementada adequadamente, você sempre terá um artefato de criação pronto
  para ser implantado, e que passou por um processo de teste padronizado.  

-----------------------------------------------------------------------------------------------------------------------------------

- O que é Continuos Deployment / Implantação Contínua?
  . A implantação contínua segue os prinicpios da entrega contínua, entretanto o usuário final é o cliente e não os Q.A.'s.
  
  . Com a implantação contínua, a atualização da produção ocorre automaticamente, sem aprovação explícita. 

-----------------------------------------------------------------------------------------------------------------------------------

o que é SCM?
 . O SCM (Source code Management, gerenciamento de código fonte) é usado para rastrear modificações em um repositório de 
 código-fonte. 
 
 . O SCM rastreia um histórico de execução de alterações em uma base de código e ajuda a resolver conflitos ao mesclar 
 atualizações de vários colaboradores. 
 
 . SCM também é sinônimo de controle de versão. 
 
-----------------------------------------------------------------------------------------------------------------------------------

O que é Amazon S3?
  . O Amazon Simple Storage Service (Amazon S3) é um serviço de armazenamento de objetos que oferece escalabilidade, 
  disponibilidade de dados, segurança e performance. 
  
  . Clientes de todos os tamanhos e setores podem usar o Amazon S3 para armazenar e proteger qualquer volume de dados para uma 
  variedade de casos de uso, como data lakes, sites, aplicações móveis, backup e restauração, arquivamento, aplicações corporativas, 
  dispositivos IoT e análises de big data. 
  
  . O Amazon S3 fornece recursos de gerenciamento para que você possa otimizar, organizar e configurar o acesso aos seus dados para 
  atender aos seus requisitos específicos de negócios, organizacionais e de compatibilidade.

  . O Amazon S3 é um serviço de armazenamento de objetos que armazena dados como objetos em buckets. Um objeto é um arquivo
  e quaisquer metadados que descrevam o arquivo. 
  
  - O que é um bucket?
    . Um bucket é um contêiner para objetos armazenados no Amazon S3.
    . Organizam o namespace do Amazon S3 no nível mais elevado.
    . Identificam a conta responsável por cobranças de transferência de dados e armazenamento.
    . Fornecem opções de controle de acesso, como políticas de bucket, listas de controle de acesso (ACLs) e pontos de acesso do S3, 
    que podem ser usados para gerenciar o acesso aos recursos do Amazon S3.
    . Serve como a unidade de agregação para relatório de uso.

  . O S3 fornece recursos que você pode configurar para oferecer suporte ao seu caso de uso específico. Você pode usar o versionamento 
  do S3 para manter várias versões de um objeto no mesmo bucket que permite que você restaure objetos excluídos ou substituídos 
  acidentalmente.

  . Os buckets e os objetos neles são privados e poderão ser acessados somente se você conceder explicitamente permissões de acesso. 
  Você pode usar políticas de bucket, políticas do AWS Identity and Access Management (IAM), listas de controle de acesso (ACLs) e 
  pontos de acesso do S3 para gerenciar o acesso.

-------------------------------------------------------------------------------------------------------------------------------------

 - O que é o Docusaurus?
  . Docusaurus é um gerador de site-estático.

  . Ele constrói um aplicativo de uma página com navegação rápida do lado do cliente, aproveitando toda a potência do React para 
  tornar seu site interativo.

  . Ele fornece recursos de documentação fora da caixa, mas pode ser usado para criar qualquer tipo de site (site pessoal, produto, 
  blog, páginas de desembarque de marketing, etc).

-------------------------------------------------------------------------------------------------------------------------------------

- O que é o Surge?
  . Surge facilita a implantação de projetos para uma qualidade de produção CDN através de Grunt, Gulp, NPM.


-------------------------------------------------------------------------------------------------------------------------------------

- O que é CDN?
  . CDN (Content Delivery Network) é uma Rede de Distribuição de Conteúdo (Estático ou Dinâmico) é um grupo de servidores que 
  permitem que os conteúdos da internet estejam facilmente disponíveis, com rapidez e segurança. 
  
  . A rede é a responsável por melhorar a experiência do usuário enquanto usa os recursos dela de forma eficiente.

-------------------------------------------------------------------------------------------------------------------------------------

- O que é Gitlab Runner?
  . O gitlab-runner é um projeto open-source escrito em golang que é usado para rodar os jobs (pipelines) e enviar o resultado 
  para o gitlab. 

  . Foi projetado para rodar na maioria dos sistemas operacionais, são eles, GNU/Linux, macOS e Windows.

-------------------------------------------------------------------------------------------------------------------------------------


- O que é trunk based development?
  . Trunk based development é um source-control branching model assim como o gitflow.

  . Mais informações: https://medium.com/@mateusdecampos/trunk-based-development-1770f5e0dfc1

-------------------------------------------------------------------------------------------------------------------------------------

- O que é cluster?
  . Um Cluster não é um software, nem algum computador específico ou mesmo um sistema operacional.

  . Nada mais é que um conceito que tem sua origem na língua inglesa e que significa aglomerar ou agrupar.

  . A ideia é utilizada para se referir a união de dois ou mais computadores com o intuito de transformá-los em um só, 
  fazendo-os trabalhar no processamento de uma tarefa mais complexa de modo unificado e simultâneo.

  . Essa união tem por objetivo melhorar a eficiência de processamento na execução de determinada ação. 
  
  . Cada computador nesse aglomerado é chamado de “nó” ou “node” e não há limites de nós em um agrupamento.

  . O software que controla o cluster, gerencia todos os computadores integrados à rede.

  . Para que isso seja eficiente, é preciso que todas as máquinas possuam o mesmo sistema operacional, mas elas não precisam 
  ser exatamente iguais.

-------------------------------------------------------------------------------------------------------------------------------------

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