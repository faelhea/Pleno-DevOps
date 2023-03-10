# Pleno-DevOps
FaseTeste

Primeiro deploy via console web!

Passos para desenvolvimento do ambiente

1 - Foi configurado uma VM, no virtual box para realizar as atividade solicitadas por e-mail.
2 - Foi instalado o Jenkins na VM.
3 - Foi criado a integracao do Jenkins com o GitHub, por ssh com troca de chave publica.
4 - Foi instalado e configurado o docker na VM.
5 - Foi ajustado as permissoes do ssh e o Jenkins
6 - Foi configurado a tarefa no jenkins para aplicar o deploy do servidor Web que esta rodando como docker compose.
7 - Foi configurado o repositorio git dev na VM e criado a branch master para gerenciar os arquivos do servidor Web.
8 - Foi realizado um deploy para o GitHub.
9 - Foi realizado um deploy do Jenkins para o servidor Web.

10 - Desafio Finalizado.

Obs: Nao foi configurado o disco persistente para o MariaDB, apenas para o wordpress.
Foi identificado varios problemas para corrigir na instalacao do Jenkins, para nao perde o prazo de entrega, foi realizado a configuracao simples do docker compose.


Hardware:
  VM - 2G Memoria, 2 vCPU.
  SO - Debian 11
  Jenkins - 2.38
  git - 1.2
  docker ce - 5.23
  
  #Fim
