<!DOCTYPE html>
<html>
<body>
  <h1>Meu Projeto</h1>
  <p>Este é um projeto de estudo que inclui um aplicativo HTML/CSS e monitoramento com Prometheus e Grafana.</p>
  <h2>Como executar</h2>
  <p>Para executar este projeto, é necessário ter o Docker e o Docker Compose instalados. Em seguida, siga os passos abaixo:</p>
  <ol>
    <li>Clone o repositório:</li>
    <pre><code>git clone https://github.com/seu-usuario/meu-projeto.git</code></pre>
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
  <li><i class="fab fa-docker"></i> <a href="https://www.docker.com/">Docker</a></li>
  <li><i class="fab fa-docker"></i> <a href="https://docs.docker.com/compose/">Docker Compose</a></li>
  <li><i class="fas fa-chart-line"></i> <a href="https://prometheus.io/">Prometheus</a></li>
  <li><i class="fab fa-grafana"></i> <a href="https://grafana.com/">Grafana</a></li>
  <li><i class="fab fa-html5"></i> HTML/CSS</li>
</ul>
</body>
</html>
