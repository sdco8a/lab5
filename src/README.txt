1 cliente pode se conectar a servidores E
1 servidor pode se conectar a varios clientes.  

ServidorImpl eh, ao mesmo tempo, servidor e cliente. (P2P)
Mas, ClienteRMI nao pode invocar novamente ServidorImpl (loop)
(ClienteRMI agora eh usado apenas pelo ServerImpl. ServerImpl eh o peer.) 

TODO: Adicionar 1 (uma) das seguintes funcionalidades:
1) Interface grafica 
2) Implementar unbind no ServidorImpl
3) ServerImpl deve ser capaz de escolher o peer.
4) Novos peers devem ser adicionados no enum Peer.
