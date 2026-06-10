# Fundamentos de AWS - Gerenciamento de EC2, AMIs e Snapshots

## Amazon EC2 e EBS
* **Amazon EC2:** Serviço que disponibiliza computadores virtuais na nuvem, chamados de instâncias.
* **Amazon EBS:** Funciona como o disco rígido (ou SSD) conectado a essas instâncias para o armazenamento dos dados.

## Imagens AMI (Amazon Machine Image)
A AMI é um modelo pré-configurado utilizado para criar novas instâncias.
* Contém o sistema operacional e as configurações iniciais necessárias.
* Permite replicar e criar múltiplos servidores idênticos de forma rápida.

## Snapshots EBS
O Snapshot é uma cópia de segurança (backup) de um disco EBS em um momento específico.
* Os snapshots são armazenados no serviço **Amazon S3**.
* Servem para recuperar arquivos e restaurar o estado do disco em caso de falhas.

## Diferença entre AMI e Snapshot
* **AMI:** É o modelo do servidor completo (sistema e configurações), usado para criar novas máquinas.
* **Snapshot:** É o backup exclusivo dos dados de um disco rígido virtual.
