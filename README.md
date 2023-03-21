# Projeto 1 - Bootcamp AWS DIO
Repositório feito para o primeiro projeto do bootcamp AWS da DIO, IaC para criação de pastas, usuários, grupos e permissões.
<br/>

### Reports:
Em minha execução pelo ubuntu 20.04 no docker, o código chegou ao final da execução mas surgiu uma mensagem de erro, mas o código está idêntico ao do professor.
"passwd: Unknown option: -crypt
passwd: Use -help for summary."

Consultando a documentação em https://www.openssl.org/docs/man1.1.1/man1/openssl-passwd.html, verifiquei que a opção -crypt não está incorreta, está em uso e não
foi depreciada, então concluí que pode ser alguma falha no contêiner que estou executando, talvez uma ausência de algum pacote.
