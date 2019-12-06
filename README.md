# DESAFIO2-PROD
desafio ansible wordpress

PLANO DE EXECUÇÃO:

1º No arquivo host, altere o ip que irá receber aplicação wordpress.  
2º Feito isso, caso rodar esse playbook em uma maquina VM, você precisará incluir sua chave SSH. 
3º Proximo passo entre na pasta config e altere o arquivo wordpress.conf e altere o campo server_name para “server_name <SUAURL>;” lembre-se de configurar o DNS publico ou para fins de teste setar o IP da maquina que rodara aplicação e SUAURL. 
4º após configuração de chave de acesso pode iniciar o ansible com o arquivo “installoff.yml”
