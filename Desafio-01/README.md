# Brincando com Ansible V1.
## _Atividades_
1 - Subir uma instancia(ubuntu free tier) na aws ou usar seu proprio PC.
2 - Instalar o Ansible.
3 - Com Ansible criar 2 instancias(ubuntu free tier) na aws.
4 - O playbook deverá conter as seguintes tarefas:
4.1 - Configuração do Security Group.
4.2 - Liberações de ssh e http.
4.3 - Instalação do Nginx(instalacao, habilitar start do servico no boot e inicializacao do servico).
4.4 - Criação de um HTML personalizado onde sera exibido o IP da server + o hostname. ##Dica, usar modulo do template com arquivo ".j2", as informações de hostname e IP deverão ser atraves do ansible facts.
4.5 - Restart do servico Nginx.
5 - Depois de Testado, NÃO ESQUECER DE DESTRUIR O AMBIENTE.

## LINKs

| Documentação | URL |
| ------ | ------ |
| Ansible Instalação | [https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html]|
| Ansible AWS | [https://docs.ansible.com/ansible/latest/collections/amazon/aws/index.html]|
| Ansible APT | [ https://docs.ansible.com/ansible/latest/collections/ansible/builtin/apt_module.html]|
