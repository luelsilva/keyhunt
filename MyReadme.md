
# atualizar e instalar as bibliotecas
sudo apt update && apt upgrade
sudo apt install git -y
sudo apt install build-essential -y
sudo apt install libssl-dev -y
sudo apt install libgmp-dev -y

# clonar o repositorio
git clone https://github.com/luelsilva/keyhunt

# entrar na pasta
cd keyhunt

# compilar o projeto
make


