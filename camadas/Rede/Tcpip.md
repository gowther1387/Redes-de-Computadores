A lista de serviços dela se da por:
* Interconexão
	Fornecer conexão logica na rede fisica(ATM e Ethernet) de maneira que as camadas acima delas abstraiam o caminho.
* Endereçamento
	Identifica o host de uma rede(Seja uma LAN ou internet).
* Roteamento
	Escolhe rotas de transferencia de pacotes(o ip utiliza o conceito de datagrama).
* Encapsulamento
	Encapsula o pacote recebido em um [[DataGramas]].
* Fragmentação
	Garante o trafego de [[DataGramas]] entre redes(sem se preocupar com a tecnologia), por isso é necessario dividir pacotes em novos segmentos de redes.

[Encaminhamento] X [Roteamento] :
* Encaminhamento
	Envolve transferir pacotes de uma entrada para uma saída
* Roteamento
	[[Roteador]]es interagem atraves de protocolos que ditam as rotas dos pacotes
A tabela de roteamento serve para indicar qual o enlace de saida que o pacote ira ser enviado.

Exemplo:
![[Pasted image 20250904112127.png]]

[[Circuitos Virtuais]] X [[DataGramas]]

* [[Roteador]]