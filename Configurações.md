# Configurando o WSL e o VSCode em um computador Windows


## 1- Instalar o VSCode  (na Microsoft Store)

instalar o `remote wsl` no vscode (nas extensões)

## 2- Instalar o UBUNTU (na Microsoft Store)

## 3- Instalar o WSL (via PowerShell)

`wsl --install` para instalar 

`sl --list --online` para ver se instalou

`wsl --set-version Ubuntu-20.04 2` definirá sua distribuição do Ubuntu 20.04 para usar o WSL 2.

`wsl -l -v` para listar distribuições instaladas

`sudo apt install code`

``code .`

## 4- Comandos para configurar o terminal (by Gabriel Silva)

- [ ]  sudo apt-get update
- [ ]  sudo apt-get upgrade -y
- [ ]  sudo apt install build-essential -y
- [ ]  sudo apt-get install clang -y
- [ ]  sudo apt-get install manpages-dev -y
- [ ]  sudo apt-get install python3 -y
- [ ]  sudo apt-get update -y
- [ ]  sudo apt-get install libbsd-dev -y
- [ ]  sudo apt-get install libncurses5-dev libncursesw5-dev -y
- [ ]  sudo apt-get install git -y
- [ ]  sudo apt update -y
- [ ]  sudo apt install valgrind -y
- [ ]  sudo apt install python3-pip -y
- [ ]  sudo apt-get install -y python-launchpadlib
- [ ]  python3 -m pip install --upgrade pip setuptools
- [ ]  python3 -m pip install norminette
- [ ]  python3 -m pip install --upgrade norminette