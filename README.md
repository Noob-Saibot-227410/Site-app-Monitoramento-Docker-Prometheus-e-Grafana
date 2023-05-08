<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-FNvvZTQjG4e7q0QDvBktAyOz6hBLFZKbBrB1ATqW63sMvaA/yXJh7A06zqXvBb4nYSSKxXvzjzJHZ7sphR8Twg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
  <h1>Site-app-Monitoramento-Docker-Prometheus-e-Grafana</h1>
  <p>Este é um projeto de estudo que inclui um aplicativo HTML/CSS e monitoramento com Prometheus e Grafana.</p>
  <h2>Como executar</h2>
  <p>Para executar este projeto, é necessário ter o Docker e o Docker Compose instalados. Em seguida, siga os passos abaixo:</p>
  <ol>
    <li>Clone o repositório:</li>
    <pre><code>git clone https://github.com/Noob-Saibot-227410/Site-app-Monitoramento-Docker-Prometheus-e-Grafana.git</code></pre>
    <li>Navegue até o diretório do projeto:</li>
    <pre><code>cd meu-projeto</code></pre>
    <li>Crie a imagem do contêiner do aplicativo:</li>
    <pre><code>docker build -t meu-app app/</code></pre>
    <li>Execute o Docker Compose:</li>
    <pre><code>docker-compose up</code></pre>
    <li>Acesse o aplicativo em um navegador:</li>
    <pre><code>http://localhost:8080</code></pre>
    <li>Acesse o painel do Grafana em um navegador:</li>
    <pre><code>http://localhost:3000</code></pre>
    <li>Use as credenciais padrão do Grafana (usuário `admin`, senha `admin`) para fazer login e configurar painéis para exibir as métricas do Prometheus.</li>
  </ol>
<h2>Tecnologias utilizadas</h2>
<ul>
  <li><a href="https://www.docker.com/"><i class="fab fa-docker"></i> Docker</a></li>
  <li><a href="https://docs.docker.com/compose/"><i class="fab fa-docker"></i> Docker Compose</a></li>
  <li><a href="https://prometheus.io/"><i class="fab fa-prometheus"></i> Prometheus</a></li>
  <li><a href="https://grafana.com/"><i class="fab fa-grafana"></i> Grafana</a></li>
  <li><i class="fab fa-html5"></i> HTML</li>
  <li><i class="fab fa-css3"></i> CSS</li>
</ul>
</body>
</html>
