eu decidi fazer diferente, decidi clonar o Juice Shop OWASP
		
os passos para instalar o Juice Shop OWASP são:

- Requisitos do sistema:

Node.js (v16 ou superior)

Git (opcional, mas recomendado para clonar o repositório)

- Passos para configurar a Loja de Sucos OWASP no Kali Linux:

Instalar dependências necessárias:

Verifique se você tem o Node.js e o npm (gerenciador de pacotes do Node.js) instalados.

- Abra o terminal e digite o seguinte para instalar as dependências:

    	sudo apt update
    
    	sudo apt install nodejs npm

- Baixar o OWASP Juice Shop:

 Clone o repositório oficial da aplicação:

    	git clone https://github.com/juice-shop/juice-shop.git
     
    	cd juice-shop

- Instalar pacotes do npm:

 No diretório do projeto, instale as dependências necessárias:

    	npm install

- Executar a aplicação:

 - Após a instalação, inicie o servidor de desenvolvimento:

   		npm start

- Acessar a Loja de Sucos:

- A aplicação estará disponível em http://localhost:3000 no seu navegador.

- A página inicial exibirá uma loja de sucos vulnerável onde você pode começar a explorar as falhas de segurança.


# Phishing para capturar senhas do Juice Shop OWASP

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://localhost:3000/#/login

  ### Resutados

![Alt text](./password "Optional title")

