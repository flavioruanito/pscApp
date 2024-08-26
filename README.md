# pscApp
Aplicação Web 

Usando:
- Três replicas
- Um container balanceado,cpu e memória
- Conexão da porta 80 para á local 8080 
  
- Um aquivo deployoment para atualizar e gerenciar os PODs
- Um arquivo services para manter a comunicação "protocolo TCP", ultilizando o LoadBalancer 
- Um arquivo configmap armazendo o BD de formato postgreslq
- Um arquivo secrets agrupando,user e password repassado (informaçao sensivél) 

