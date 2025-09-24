<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Madan | DevOps Engineer</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #fdfbfb 0%, #ebedee 100%);
      color: #333;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      flex-direction: column;
    }
    .intro {
      background: black;
      text-align: center;
      margin-bottom: 30px;
      padding: 3rem 5rem;
      color: white;
    }
    .intro h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    .intro h1 .hi {
      display: inline-block;
      transform-origin: 70% 70%;
      animation: wave 1.5s linear -0.5s infinite;
    }
    .intro h3 {
      font-weight: 400;
    }
    @keyframes wave {
      0% { transform: rotate(0.0deg) }
      10% { transform: rotate(14.0deg) }
      20% { transform: rotate(-8.0deg) }
      30% { transform: rotate(14.0deg) }
      40% { transform: rotate(-4.0deg) }
      50% { transform: rotate(10.0deg) }
      60% { transform: rotate(0.0deg) }
      100% { transform: rotate(0.0deg) }
    }
    .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      max-width: 800px;
    }
    .skills a img {
      width: 50px;
      height: 50px;
      transition: transform 0.3s, box-shadow 0.3s;
      border-radius: 8px;
    }
    .skills a img: hover {
      transform: scale(1.2);
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    }
    footer {
      margin-top: 40px;
      font-size: 0.9rem;
      color: #777;
    }
  </style>
</head>
<body>
  
  <div class="intro">
    <h1>Hi there, my name is Madan <span class="hi">👋</span></h1>
    <h3>A passionate DevOps Engineer from Nepal</h3>
  </div>

  <div class="skills">
    <a href="https://git-scm.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git"></a>
    <a href="https://www.docker.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="Docker"></a>
    <a href="https://www.jenkins.io" target="_blank"><img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="Jenkins"></a>
    <a href="https://kubernetes.io" target="_blank"><img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="Kubernetes"></a>
    <a href="https://www.linux.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux"></a>
    <a href="https://aws.amazon.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS"></a>
    <a href="https://www.gnu.org/software/bash/" target="_blank"><img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="Bash"></a>
    <a href="https://www.w3schools.com/css/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3"></a>
    <a href="https://grafana.com" target="_blank"><img src="https://www.vectorlogo.zone/logos/grafana/grafana-icon.svg" alt="Grafana"></a>
    <a href="https://www.w3.org/html/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5"></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript"></a>
    <a href="https://www.mysql.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL"></a>
    <a href="https://www.nginx.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="Nginx"></a>
    <a href="https://www.python.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python"></a>
    <a href="https://redis.io" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="Redis"></a>
  </div>

  <footer>
    <p>🚀 Always learning, always building.</p>
  </footer>

</body>
</html>
