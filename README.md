# Phishing Facebook

### Ferramentas utilizadas
- Kali Linux
- setoolkit

### Atenção!
Apenas para fins educacionais, o uso dessa prática é ilegal e não me responsabilizo por danos causados.
Criando um Phishing para capturar senha do Facebook, neste método iremos utilizar a ferramenta setoolkit para criar uma página de login falsa.

### Passo a passo
- Entrar como root: Opção 1 ``` sudo su ```
- Iniciando o ``` setoolkit ```
- Selecionando o tipo de ataque: Opção 1 ``` Social-Engineering Attacks ```
- Selecionando o vetor de ataque - de onde vai partir: Opção 2 ``` Web Site Attack Vectors ```
- Selecionando o método de ataque: Opção 3 ```Credential Harvester Attack Method ```
- Confirmando o método de ataque: Opção 2 ``` Site Cloner ```
- Como iremos rodar o site falso em um servidor, precisamos informar o IP da máquina. Já é sugerido na linha de comando, basta dar um "Enter" ``` ifconfig ```
- Indicar a URL a ser clonada: http://www.facebook.com
