# Solutions Architect
### via ADVC (Cloud Faster Academy - Dan Rezende)

### Agenda primeira gravação
Fazer analise:
- AWS well architect framework
- DynamoDB, dabatabase NoSQL com alta disponibilidade.
- Internet Gateway -  Toda tabela subnet é configurada no IG para saida para internet
- NAT Gateway é utilizado na Public subnet para sair com conexão para acessos
- Saber qual a rota de entrada e saida dos serviços
- VPC endpoint para acesso entre serviços, exemplo: uma EC2 acessar DynamoDB dentro da AWS, sem passar pela internet pelo NAT gateway até o Endpoit do DynamoDB
- Custo de dataTransfer - Analisar entrada/saida e seus custos
- Endpoint Gateway de Internet integrado em S3 e DynamoDB free
- OBS para o EXAME:
    -  30% Design de arquitetura seguras; serviços de segurança
    -  26% Design de arquiteturas resilientes; multiAz, serviços gerenciados, s3
    -  24% Designde arquiteturas de alta performace; Como escala, auto scaling e balanceador de carga
    -  20% Design de arquiteturas economicas; usar o AS para ficar eficiente, quebrar app em lambda, disco alterar para EFS, EBS e outros, saber analisar

  - Vide Guia do EXAME

