# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 02/04/2024

Empresa: Abstergo Industries 

Responsável: Daynara Mira

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por ***Daynara Mira***. O objetivo do projeto é elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon EC2
- O EC2 é um serviço que fornece capacidade redimensionável na nuvem. Com o EC2 é possivel gerenciar seu próprio servidor virtual, podendo escolher as configurações de armazenamento, rede e segurança mais adequadas para o seu negócio, assim reduzindo os custos de hardware.
O Amazon EC2 fornece recursos de alto nível, dentre eles estão: instâncias, que são os servidores virtuais; imagens de máquina da amazon(AMI), modelos pré-configurados da instância com os componentes empacotados necessários para o servidor; tipos de instância, que são as coonfigurações de capacidade do CPU, memória, armazenamento, redes e hardware gráfico; pares de chaves, são chaves usadas para proteger as informações de login das instâncias. A AWS armazena a chave pública, e o usuário fica responsável por armazenar a chave privada; volumes de armazenamento de instâncias, volume dos dados temporários (cache) que são excluídos quando a instância é interrompida; volumes do Amazon EBS, volume dos armazenamentos persistentes para os dados usando o Amazon Elastic Block Store; zonas de disponibilidade, os locais físicos dos recursos; grupos de segurança, firewall virtual que permite especificar configurações de conexões IP; endereços IP elásticos, endereços de IPv4 estáticos.
- O Amazon EC2 é extremamente versátil, ele oferece um controle completo dos recursos computacionais o que possibilita o seu uso para as mais variadas tarefas, como: Processamento de dados e midias, hospedagem de sites, desenvolvimento e testes de apps, hospedagem de banco de dados, aprendizado de máquina, etc.

Etapa 2: 
- Amazon QLDB 
- Amazon Quantum Ledger Database, QLDB, é um banco de dados ledger, que fornece um log de transações transparentes, imutável e com criptografia que pertence a uma autoridade central confiável. O QLDB possui quatro benefícios essênciais: imutabilidade e transparência, os dados são criptogracriptograficamente verificáveis, é fácil de usar e é servless.
- Com O QLDB é possível armazenar tarnsações finaceiras criando um registro completo e preciso de todas as transações realizadas; reconciliar os sistemas de cadeia de suprimentos registrando o histórico de cada transação e fornecendo os detalhes de lotes fabricados, enviados, armazenados e vendidos; manter histórico de declarações, é possível rastreiar uma declaração durante sua vida útil e verificar criptograficamente a integridade dos dados para tornar a aplicação resiliente à erros de entrada e manipulação de dados; centralizar os registros digitais implementando um sistema de registro de aplicação para criar um registro completo e centralizado sobre detalhes dos funcionários.

Etapa 3: 
- Amazon SQS
- O Amazon SQS, Simple Queue Service, é um serviço de mensageria gerenciadas para microsserviços, sistemas distribuidos e aplicações com tecnologia sem servidor. O SQS tem como benefícios: segurança, durabilidade, disponibilidade, escalabilidade, confiabilidade e personalização. Esses benefícios permitem o envio, armazenamento e recebimento de mensagens entre componentes de softawre em qualquer volume, sem perda de mensagens e sem a necessidade de que outros serviços estejam disponiveis.
- Com o SQS é possível aumentar a confiabilidade e escala da aplicação desacoplando e conectando componentes usando filas, desacoplar microsserviços e processar aplicaçoes orientadas a eventos separando o front-end do back-end para que os clientes obtenham uma resposta imediata enquanto as transações são processadas em segundo plano, garantir que o trabalho seja concluído de  forma econômica e dentro do prazo, manter a ordem das mesnsagens com desduplicação.

## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries tem como esperado a melhoria das interações, tanto internas quanto externas, da empresa e a redução dos custos com hardware*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
[Amazon EC2](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/concepts.html#ec2-features)

[Amazon EC2 casos de uso](https://aws.amazon.com/pt/ec2/faqs/)

[Amazon QLDB casos de uso](https://aws.amazon.com/pt/qldb/)

[Amazon QLDB](https://docs.aws.amazon.com/pt_br/qldb/latest/developerguide/what-is.html)

[Bancos de dados da AWS](https://aws.amazon.com/pt/getting-started/decision-guides/databases-on-aws-how-to-choose/)

[Vídeo sobre o QLDB](https://www.youtube.com/watch?v=blIku5CWYzU)

[Amazon SQS](https://aws.amazon.com/pt/sqs/)

[Benefícios do SQS](https://docs.aws.amazon.com/pt_br/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-benefits.html)

#### Assinatura do Responsável pelo Projeto:

Daynara Mira.