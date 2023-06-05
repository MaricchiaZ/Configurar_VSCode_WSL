# Configurando o WSL e o VSCode em um computador Windows

O Ubuntu é um sistema operacional baseado em Linux amplamente utilizado por desenvolvedores, cientistas de dados e profissionais de TI em todo o mundo.

O WSL (Windows Subsystem for Linux) é uma camada de compatibilidade do Windows que permite executar um ambiente Linux nativo no Windows. Ele fornece uma interface entre o sistema operacional Windows e o subsistema Linux, permitindo que você execute aplicativos e comandos do Linux no seu computador com Windows. O WSL é uma solução conveniente para desenvolvedores que desejam usar ferramentas e recursos do Linux enquanto mantêm a funcionalidade do Windows.

Quando você usa o VSCode (Visual Studio Code) no Windows com o WSL, você pode aproveitar as vantagens das ferramentas e recursos do Ubuntu (ou qualquer outra distribuição Linux suportada pelo WSL) diretamente no seu ambiente de desenvolvimento integrado. Isso permite que você execute comandos do terminal do Linux, use utilitários e bibliotecas específicos do Linux e trabalhe com fluxos de trabalho que são mais comuns em ambientes Linux.

Além disso, o VSCode possui extensões e integrações específicas para o desenvolvimento no ambiente Linux, permitindo que você escreva, depure e teste seu código de maneira eficiente. Ao combinar o Ubuntu com o WSL e o VSCode, você pode obter o melhor dos dois mundos: a flexibilidade e a estabilidade do Ubuntu e a interface e a compatibilidade do Windows.

Em resumo, usar o Ubuntu com o WSL no VSCode em computadores com Windows oferece uma solução poderosa e conveniente para desenvolvedores que desejam trabalhar com ferramentas e recursos do Linux em um ambiente Windows, sem a necessidade de dual boot ou de manter dois sistemas operacionais separados.
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