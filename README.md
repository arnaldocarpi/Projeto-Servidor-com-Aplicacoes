## PROJETO SERVIDOR DE SITES E OUTROS SERVIÇOS.

Esse projeto consiste na construção de forma completa de um servidor web, desde a parte de infraestrutura até a virtualização de sistemas, configuração de ambientes,
instalação e configuração de aplicações para hospedar sites e caso necessário, outros serviços.

### A infraestrutura consiste em:

1. - `RouterBoard:` Acesso a internet via PPPoE + ip publico fixo. (Essa RB também gerencia as portas dos servidores e o firewall.)
2. - `SERVIDOR:` 1x Intel Celeron (modelo), 4GB RAM - 1 SSD 128GB, (Vai ser necessário fazer um upgrade para rodar mais de uma maquina virtual) 

### Sistemas virtualizados via PROXMOX:

1. `Ubuntu Server:` (SITE DE ESTUDO - CLONE MELHORADO ÁREA DO ALUNO UNOPAR)
    - `APACHE` Para disponibilizar o site no servidor WEB
    - `Repositório:` [Repositório Clone melhorado Unopar](https://github.com/arnaldocarpi/carteirinha-unopar)
    - `Mantenedores:` [Github Arnaldo Carpi](https://github.com/arnaldocarpi) - [Github Gutemberg Oliveira](https://github.com/OliveiraGutemberg)
    - `Fixtures:` Site atualizado automaticamente via Github Actions quando houver alguma alteração na branche main;
        -   SSL habilitado
    - `Trabalhando:` IP V6 no servidor e área de cadastro.

Acesse o site BETA: [Clone Unopar](https://loginunopar.zapto.org:444)
