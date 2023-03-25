## Projeto 1 - Bootcamp AWS DIO

### Descrição do Desafio

Neste projeto iremos criar um script onde toda a infraestrutura de usuários, grupos de usuários, diretórios e permissões serão criadas automaticamente. Será realizado o upload do arquivo de script no GitHub para futuras reutilizações do script. Sendo assim, toda nova máquina virtual que for iniciada já estará pronta para uso quando o script for executado.


### Reports
Em minha execução pelo ubuntu 20.04 no docker, o código chegou ao final da execução mas surgiu a mensagem de erro: "passwd: Unknown option: -crypt
passwd: Use -help for summary.", mas o código está idêntico ao demonstrado pelo professor.


Consultando a documentação em https://www.openssl.org/docs/man1.1.1/man1/openssl-passwd.html, verifiquei que a opção -crypt não está incorreta, 
está em uso e não foi depreciada, então concluí que pode ser alguma falha no contêiner que estou executando, talvez uma ausência de algum pacote.
