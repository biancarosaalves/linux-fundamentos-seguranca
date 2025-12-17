# Usuários e Grupos no Linux
 No Linux, cada usuário possui um identificador único chamado UID ( User ID). O usuário root possui UID 0 e tem privilégios administrativos totais.

 ## Importância para a Segurança 
 Permitir que apenas o usuário root possua  UID O reduz o impacto de um possivel comprometimento do sistema. 

 ## Comandos Básicos
 Criar usuário:
  '' bash 
  sudo  useradd -m - s /bin/bash/ nome_usuario
  sudo passwd nome_usuario
