#Exemplo de Cliente e Servidor RMI

Para rodar o exemplo, precisa-se configurar as seguintes variáveis de VM tanto para o projeto RMIServer e RMIClient

##Variaveis de VM Server

	-Djava.security.policy=./src/server.policy

##Variaveis de VM Client

	-Djava.security.policy=./src/client.policy

Esse arquivo de policy está com todas as permissões para testes.

Dentro da pasta do RMIServer, iniciar o RMI Registry

Comando:
	
	start rmiregistry


##Fonte de estudos:
https://docs.oracle.com/javase/tutorial/rmi/overview.html