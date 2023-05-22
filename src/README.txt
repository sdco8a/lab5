Peer.java eh o ServerImpl.java dos laboratorios anteriores, porem
agora cada Peer.java pode se conectar diretamente a outro Peer.java. 
  

Peer.java eh, ao mesmo tempo, servidor e cliente. (P2P)
Mas, ClienteRMI nao pode invocar novamente ServidorImpl (loop)
(ClienteRMI agora eh usado apenas pelo Peer.java, que eh o peer.) 

TODO: Adicionar 1 (uma) das seguintes funcionalidades:
1) Interface grafica 
2) Implementar unbind no ServidorImpl
3) ServerImpl deve ser capaz de escolher o peer.
4) Novos peers devem ser adicionados no enum Peer.
