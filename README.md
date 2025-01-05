# desafio-phishing
Projeto criado para o clone de uma pagina do Facebook Fake simulando assim o processo de captura de usuarios e senhas.

Ferramentas Utilizadas
S.O -> Kali Linux / Parrot Linux
Tool -> setoolkit (Social-Engineer Toolkit) é uma ferramenta popular para realizar testes de engenharia social e simulação de ataques cibernéticos (instruções de 

Procedimento
1) elevação de privilégios como root -> sudo su
2) inicando SET -> setoolkit
3) tipo de ataque (opção 1) -> Social-Engineering Attacks
4) Qual será o ataque (opção 2) ->Web Site Attack Vectors
5) Metodologia do ataque (opção 3) -> Credential Harvester Attack Method
6) Qual ataque (opção 2) -> Site Cloner
7) Será questionado o endereço IP, o importante é ser um ip acessado externamente para que haja a coleta dos dados -> ifconfig
8) Pagina que será clonada: http://www.facebook.com

Em seguida devemos abrir o navegador e no endereço colocar o endereço detectado pelo ifconfig (maquina kali/parrot). A pagina aberta será a pagina clonada pelo SET. Ao entrar com seu usuario e senha, será registrado os dados assim como mostrado na figura em anexo.

![vampiro01_terminal](https://github.com/user-attachments/assets/ad2c65f5-d119-48a1-8a28-453d6ffe883f)
