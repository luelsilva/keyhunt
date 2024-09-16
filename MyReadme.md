
# atualizar e instalar as bibliotecas
apt update && apt upgrade
apt install git -y
apt install build-essential -y
apt install libssl-dev -y
apt install libgmp-dev -y

# clonar o repositorio
https://github.com/luelsilva/keyhunt

# entrar na pasta
cd keyhunt

# compilar o projeto
make


