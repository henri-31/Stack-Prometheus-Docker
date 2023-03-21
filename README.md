##**Stack Prometheus Docker**
Este projeto consiste em um conjunto de serviços que utilizam o Docker Compose para executar o Prometheus e outras ferramentas relacionadas para monitorar a infraestrutura e as aplicações em um ambiente de desenvolvimento ou produção.

**Pré-requisitos**
Para executar este projeto, você precisará ter instalado em sua máquina o Docker e o Docker Compose. Certifique-se também de que as portas 9090 e 3000 estejam disponíveis em sua máquina.

**Instalação e execução**


1.Clone o repositório em sua máquina local:

**git clone https://github.com/henri-31/Stack-Prometheus-Docker.git**


2.Navegue até o diretório do projeto:

**cd Stack-Prometheus-Docker**


3.Execute o comando abaixo para construir e executar os containers Docker:

**docker-compose up -d**


4.Aguarde alguns instantes para que todos os serviços sejam inicializados corretamente. Para verificar se os containers estão sendo executados corretamente, execute o seguinte comando:

**docker ps**


5.Abra o navegador e acesse o Prometheus na URL:

**http://localhost:9090/**


6.Abra o navegador e acesse o Grafana na URL:

**http://localhost:3000/**


7.Faça login no Grafana com as credenciais padrão (usuário: admin, senha: admin) e configure a fonte de dados Prometheus.

8.Importe um dashboard para começar a monitorar suas aplicações. Existem vários dashboards disponíveis na internet.


##**Parando o projeto**
Para parar e remover os containers Docker, execute o seguinte comando:

**docker-compose down**


Este comando irá parar e remover todos os containers, redes e volumes relacionados a este projeto.

Espero que estas instruções ajudem você a executar este projeto sem problemas. Se precisar de mais ajuda, não hesite em abrir uma issue neste repositório.





