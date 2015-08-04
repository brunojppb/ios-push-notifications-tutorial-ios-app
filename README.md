# iOS 8 Push Notifications com Rails Backend e Swift

Ao criar aplicações mobile, uma das principais funcionalidades que o desenvolvedor pode e deve explorar é a notificação. Basicamente, temos dois tipos de notificação:

 - Notificações Locais:
  São armazenadas no próprio sistema operacional do aparelho e não dependem de webservices ou conexão com a internet.

 - Notificações Remotas(Push Notifications):
  Exigem que o desenvolvedor implemente um webservice que envie essas mensagens para um PNS(Push Notification Service), em nosso caso será APNS(Apple Push Notification Service) que encaminhará essa mensagens para os devices.

 Precisei implementar notificações remotas na minha ultima aplicação iOS e sinto que provavelmente precisar reler esse post para refrescar a memória. Nosso foco será apenas em Notificações remotas, pois estou preparando outro post exclusivamente sobre notificações locais.

 Mais detalhes em [meu blog](http://www.bpaulino.com.br/)
