# Deploy Bluemix IBM Cloud com Integração Contínua

https://github.com/thiagomnc/deploy-bluemix.git

# Instalação do CF CLI
https://docs.cloudfoundry.org/cf-cli/install-go-cli.html

# Conectando no IBM Cloud via CF CLI
https://github.com/cloudfoundry/cli
cf -v
cf api https://api.ng.bluemix.net
cf login --sso
One Time Code (Get one at https://login.ng.bluemix.net/UAALoginServerWAR/passcode)>
Authenticating...

# Deploy de uma Aplicação
cf push

# Comandos Úteis do CF CLI
cf apps
cf logs faculdade-impacta-thiagomnc --recent

# Ativando a Integração contínua no IBM Cloud:
Entrar em:
> IBM Cloud para listar as Aplicações
> Overview
> Continuous delivery
> Enable (para habilitar free)

# Terminal via CF CLI
cf ssh faculdade-impacta-thiagomnc

Obrigado!!!

# Comandos úteis do git
git clone https://github.com/thiagomnc/exemplo-nodejs.git
git add .
git commit -m "primeiro commit"
git push