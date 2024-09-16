# Simulado 15

Clique no botão **Resposta** para a resposta correta e sua explicação.

Se este simulado foi útil para você, compartilhe com outros e reaja abaixo.

---

1. Como os clientes se beneficiam das economias de escala massivas da Amazon?
    - A. Reduções periódicas de preços como resultado das eficiências operacionais da Amazon
    - B. Novos tipos de instâncias Amazon EC2 que fornecem o hardware mais recente
    - C. A capacidade de aumentar e diminuir a escala conforme necessário
    - D. Maior confiabilidade no hardware subjacente das instâncias Amazon EC2

    <details markdown=1><summary markdown="span">Resposta</summary>

    Resposta correta: A

    </details>

2. Quais serviços da AWS podem ser usados para reunir informações sobre a atividade da conta AWS? (Selecione DOIS.)
    - A. Amazon CloudFront
    - B. AWS Cloud9
    - C. AWS CloudTrail
    - D. AWS CloudHSM
    - E. Amazon CloudWatch

    <details markdown=1><summary markdown="span">Resposta</summary>

      Resposta correta: C, E

      Explicação:
      - A AWS oferece uma solução que usa o AWS CloudTrail para registrar a atividade da conta, o Amazon Kinesis para calcular e transmitir métricas em tempo real, e o Amazon DynamoDB para armazenar de forma durável os dados calculados.
      - As métricas são calculadas para chamadas de API de criação, modificação e exclusão de mais de 60 serviços AWS suportados.
      - A solução também inclui um painel que visualiza a atividade da conta em tempo real.

      Referência: <https://aws.amazon.com/solutions/real-time-insights-account-activity/>

    </details>

3. Quais das seguintes tarefas de TI comuns a AWS pode cobrir para liberar os recursos de TI da empresa? (Selecione DOIS.)
    - A. Aplicar patches em softwares de banco de dados
    - B. Testar versões de aplicativos
    - C. Fazer backup de bancos de dados
    - D. Criar esquemas de banco de dados
    - E. Executar testes de penetração

    <details markdown=1><summary markdown="span">Resposta</summary>

    Resposta correta: A, C

    </details>

4. Em qual cenário as Instâncias Spot do Amazon EC2 devem ser usadas?
    - A. Uma empresa quer mover seu site principal para a AWS a partir de um servidor web on-premises.
    - B. Uma empresa tem uma série de serviços de aplicativos cujo Acordo de Nível de Serviço (SLA) exige 99,999% de tempo de atividade.
    - C. O banco de dados legado muito utilizado de uma empresa está atualmente sendo executado on-premises.
    - D. Uma empresa tem vários trabalhos esporádicos e interruptíveis que estão atualmente usando Instâncias On-Demand.

    <details markdown=1><summary markdown="span">Resposta</summary>

    Resposta correta: D

    Explicação: <https://docs.aws.amazon.com/whitepapers/latest/cost-optimization-leveraging-ec2-spot-instances/spot-instance-interruptions.html>

    </details>

5. Qual recurso da AWS um cliente deve utilizar para alcançar alta disponibilidade de um aplicativo?
    - A. AWS Direct Connect
    - B. Availability Zones
    - C. Data centers
    - D. Amazon Virtual Private Cloud (Amazon VPC)

    <details markdown=1><summary markdown="span">Resposta</summary>

    Resposta correta: B

    Explicação:
    - Isso é para alcançar Alta Disponibilidade para qualquer aplicativo web (neste caso, SwiftCode) implantado na AWS.
    - As seguintes características estarão presentes:
    - Alta disponibilidade em várias instâncias/múltiplas zonas de disponibilidade.
    - Auto Scaling de instâncias (escalar para cima e para baixo) com base no número de solicitações recebidas.
    - Segurança adicional para as instâncias/banco de dados que estão em produção.
    - Sem impacto para os usuários finais durante a implantação de novas versões de código.
    - Sem impacto durante a aplicação de patches nas instâncias.

    </details>

6. Qual é o plano mínimo de Suporte da AWS que inclui o Gerenciamento de Eventos de Infraestrutura sem custos adicionais?
    - A. Enterprise
    - B. Business
    - C. Developer
    - D. Basic

    <details markdown=1><summary markdown="span">Resposta</summary>

    Resposta correta: B

    Explicação: <https://aws.amazon.com/premiumsupport/plans/>

    </details>

7. Qual serviço da AWS pode servir um site estático?
    - A. Amazon S3
    - B. Amazon Route 53
    - C. Amazon QuickSight
    - D. AWS X-Ray

    <details markdown=1><summary markdown="span">Resposta</summary>

    Resposta correta: A

    Explicação:
    - Você pode hospedar um site estático no Amazon Simple Storage Service (Amazon S3). Em um site estático, páginas da web individuais incluem conteúdo estático.
    - Elas também podem conter scripts do lado do cliente. Em contraste, um site dinâmico depende do processamento do lado do servidor, incluindo scripts como PHP, JSP ou ASP.NET. O Amazon S3 não suporta scripts do lado do servidor.

    Referência: <https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html>

    </details>

8. Como a AWS reduz o tempo para provisionar recursos de TI?
    - A. Fornece uma plataforma online de tickets de TI para solicitações de recursos.
    - B. Suporta serviços automáticos de validação de código.
    - C. Oferece a capacidade de provisionar programaticamente recursos existentes.
    - D. Automatiza o processo de solicitação de recursos a partir de uma lista de fornecedores de TI da empresa.

    <details markdown=1><summary markdown="span">Resposta</summary>

    Resposta correta: C

    </details>

9. Para que podem ser usadas as AWS edge locations? (Selecione DOIS.)
    - A. Hospedar aplicativos
    - B. Entregar conteúdo mais próximo dos usuários
    - C. Executar serviços de cache de banco de dados NoSQL
    - D. Reduzir o tráfego no servidor ao armazenar respostas em cache
    - E. Enviar mensagens de notificação aos usuários finais

    <details markdown=1><summary markdown="span">Resposta</summary>

    Resposta correta: B, D

    Explicação:
    - O CloudFront entrega seu conteúdo por meio de uma rede mundial de data centers chamados edge locations. Quando um usuário solicita conteúdo que você está servindo com o CloudFront, o usuário é direcionado para a edge location que oferece a menor latência (atraso), para que o conteúdo seja entregue com o melhor desempenho possível.

    Referência: <https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html>

    </details>

10. O que pode limitar o acesso a um bucket do Amazon Simple Storage Service (Amazon S3) a usuários específicos?
    - A. Um par de chaves pública e privada
    - B. Amazon Inspector
    - C. Políticas do AWS Identity and Access Management (IAM)
    - D. Security Groups

    <details markdown=1><summary markdown="span">Resposta</summary>

    Resposta correta: C

    Explicação:
    - Para permitir que os usuários realizem ações no S3 a partir de endpoints VPC ou endereços IP, você deve conceder permissões de nível de usuário explicitamente.
    - Você pode conceder permissões de nível de usuário em uma política do AWS Identity and Access Management (IAM) ou em outra declaração na política do bucket.

    Referência: <https://aws.amazon.com/premiumsupport/knowledge-center/block-s3-traffic-vpc-ip/>

    </details>

11. Uma solução capaz de suportar o crescimento de usuários, tráfego ou tamanho de dados sem queda de desempenho está alinhada com qual princípio de arquitetura em nuvem?
   - A. Pensar em paralelo
   - B. Implementar elasticidade
   - C. Desacoplar seus componentes
   - D. Projetar para falhas

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: B

   Explicação: <https://d1.awsstatic.com/whitepapers/AWS_Cloud_Best_Practices.pdf>

   </details>

---

12. Qual das seguintes tarefas é responsabilidade da AWS?
   - A. Criptografar dados do lado do cliente
   - B. Configurar funções do AWS Identity and Access Management (IAM)
   - C. Proteger o hipervisor do Amazon EC2
   - D. Definir políticas de senha para os usuários

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: C

   Explicação:
   - No EC2, a oferta IaaS da AWS, tudo da camada do hipervisor para baixo é responsabilidade da AWS.
   - Aplicativos mal codificados, sistemas operacionais mal configurados ou configurações de firewall inseguras do cliente não afetam o hipervisor, apenas as máquinas virtuais do cliente executadas nesse hipervisor.

   Referência: <https://www.mindpointgroup.com/blog/the-aws-shared-responsibility-model-part-1-security-in-the-cloud/>

   </details>

---

13. Um benefício da precificação On-Demand do Amazon Elastic Compute Cloud (Amazon EC2) é:
   - A. A capacidade de fazer lances por um custo horário mais baixo.
   - B. Pagar uma taxa diária, independentemente do tempo usado.
   - C. Pagar apenas pelo tempo utilizado.
   - D. Pré-pagar por instâncias e pagar uma taxa horária mais baixa.

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: C

   Explicação:
   - As reservas de capacidade On-Demand têm o mesmo preço que o uso equivalente da instância On-Demand.
   - Se uma reserva de capacidade for totalmente utilizada, você paga apenas pelo uso da instância e nada pela reserva de capacidade.
   - Se uma reserva de capacidade for parcialmente utilizada, você paga pelo uso da instância e pela parte não utilizada da reserva.

   Referência: <https://aws.amazon.com/ec2/pricing/on-demand/>

   </details>

---

14. Um administrador precisa implantar rapidamente uma solução de TI popular e começar a usá-la imediatamente. <br/> Onde o administrador pode encontrar assistência?
   - A. Documentação do AWS Well-Architected Framework
   - B. Amazon CloudFront
   - C. AWS CodeCommit
   - D. Implementações de referência AWS Quick Start

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: D

   Explicação:
   - O AWS Quick Starts é desenvolvido por arquitetos de soluções da AWS e parceiros para ajudar a implantar tecnologias populares na AWS, com base nas melhores práticas de segurança e alta disponibilidade da AWS.
   - Esses aceleradores reduzem centenas de procedimentos manuais em apenas alguns passos, para que você possa construir seu ambiente de produção rapidamente e começar a usá-lo imediatamente.

   Referência: <https://aws.amazon.com/quickstart/?quickstart-all.sort-by=item.additionalFields.updateDate&quickstart-all.sort-order=desc>

   </details>

---

15. Qual dos seguintes serviços está na categoria de plataforma serverless da AWS?
   - A. Amazon EMR
   - B. Elastic Load Balancing
   - C. AWS Lambda
   - D. AWS Mobile Hub

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: C

   Explicação:
   - A AWS oferece um conjunto de serviços totalmente gerenciados que você pode usar para construir e executar aplicações serverless.
   - Aplicações serverless não exigem provisionamento, manutenção e administração de servidores para componentes de backend, como computação, bancos de dados, armazenamento, processamento de stream, filas de mensagens e mais.

   Referência: <https://aws.amazon.com/serverless/>

   </details>

---

16. Quais serviços fazem parte da plataforma serverless da AWS?
   - A. Amazon EC2, Amazon S3, Amazon Athena
   - B. Amazon Kinesis, Amazon SQS, Amazon EMR
   - C. AWS Step Functions, Amazon DynamoDB, Amazon SNS
   - D. Amazon Athena, Amazon Cognito, Amazon EC2

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: C

   Explicação:
   - A AWS oferece um conjunto de serviços totalmente gerenciados para construir e executar aplicações serverless.
   - A plataforma serverless inclui: AWS Lambda, Amazon S3, DynamoDB, API Gateway, Amazon SNS, AWS Step Functions, Amazon Kinesis, e ferramentas e serviços de desenvolvimento.

   Referência: <https://aws.amazon.com/serverless/>

   </details>

---

17. No modelo de responsabilidade compartilhada, qual das seguintes é um controle compartilhado entre o cliente e a AWS?
   - A. Controles físicos
   - B. Gerenciamento de patches
   - C. Segurança da zona
   - D. Auditoria de data centers

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: B

   Explicação:
   - Controles compartilhados são aqueles que se aplicam tanto à camada de infraestrutura quanto às camadas do cliente, mas em contextos ou perspectivas completamente separadas.
   - A AWS é responsável pelos patches na infraestrutura, e o cliente é responsável por patching no sistema operacional e aplicativos.

   Referência: <https://aws.amazon.com/compliance/shared-responsibility-model/>

   </details>

---

18. Para que podem ser usadas as localizações de borda da AWS? (Selecione DUAS.)
   - A. Hospedar aplicativos
   - B. Entregar conteúdo mais perto dos usuários
   - C. Executar serviços de cache de banco de dados NoSQL
   - D. Reduzir o tráfego no servidor por meio do cache de respostas
   - E. Enviar mensagens de notificação para os usuários finais

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: BD

   Explicação:
   - O CloudFront entrega seu conteúdo através de uma rede mundial de data centers chamados localizações de borda.
   - Quando um usuário solicita conteúdo servido com o CloudFront, ele é roteado para a localização de borda que oferece a menor latência.

   Referência: <https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html>

   </details>

---

19. Qual tecnologia permite ajustar a capacidade de computação conforme as cargas mudam?
   - A. Load balancing
   - B. Failover automático
   - C. Round robin
   - D. Auto Scaling

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: D

   Explicação:
   - O AWS Auto Scaling monitora suas aplicações e ajusta automaticamente a capacidade para manter o desempenho previsível ao menor custo possível.

   Referência: <https://aws.amazon.com/autoscaling/>

   </details>

---

20. Quais serviços da AWS são definidos como globais em vez de regionais? (Selecione DUAS.)
   - A. Amazon Route 53
   - B. Amazon EC2
   - C. Amazon S3
   - D. Amazon CloudFront
   - E. Amazon DynamoDB

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: AD

   Explicação: <http://jayendrapatil.com/aws-global-vs-regional-vs-az-resources/>

   </details>

---

21. Qual serviço da AWS você usaria para obter relatórios e certificados de conformidade?
   - A. AWS Artifact
   - B. AWS Lambda
   - C. Amazon Inspector
   - D. AWS Certificate Manager

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: A

   Explicação:
   - O AWS Artifact é o seu recurso central para informações de conformidade, fornecendo acesso sob demanda aos relatórios de segurança e conformidade da AWS.

   Referência: <https://aws.amazon.com/artifact/>

   </details>

---

22. No modelo de responsabilidade compartilhada, quais das seguintes tarefas são de responsabilidade do cliente da AWS? (Selecione DUAS.)
   - A. Garantir que os dados da aplicação sejam criptografados em repouso
   - B. Garantir que os servidores NTP da AWS estejam ajustados para o horário correto
   - C. Garantir que os usuários tenham recebido treinamento de segurança no uso dos serviços da AWS
   - D. Garantir que o acesso aos data centers seja restrito
   - E. Garantir o descarte adequado do hardware

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: AC

   Explicação: <https://aws.amazon.com/compliance/shared-responsibility-model/>

   </details>

---

23. Qual serviço da AWS pode ser usado para lançar instâncias manualmente com base nos requisitos de recursos?
  

 - A. Amazon Lightsail
   - B. AWS Config
   - C. Amazon Elastic Compute Cloud (Amazon EC2)
   - D. AWS CloudFormation

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: C

   </details>

---

24. Quais opções de compra podem economizar até 90% nos custos de computação do Amazon EC2?
   - A. Instâncias reservadas
   - B. Instâncias dedicadas
   - C. Instâncias Spot
   - D. Instâncias On-Demand

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: C

   Explicação:
   - As Instâncias Spot do Amazon EC2 permitem que você aproveite a capacidade de computação não utilizada na AWS e economize até 90% em comparação com os preços On-Demand.

   Referência: <https://aws.amazon.com/ec2/spot/>

   </details>


---

**25. Quais são os benefícios financeiros de usar a AWS? (Selecione DUAS.)**
   - A. Redução do Custo Total de Propriedade (TCO).
   - B. Aumento do gasto de capital (capex).
   - C. Redução do gasto operacional (opex).
   - D. Planos de pagamento diferidos para startups.
   - E. Linhas de crédito para startups.

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: A, C

   </details>

---

**26. De acordo com o modelo de responsabilidade compartilhada da AWS, qual das opções a seguir é totalmente responsabilidade da AWS?**
   - A. Aplicação de patches no sistema operacional convidado.
   - B. Conscientização e treinamento sobre segurança.
   - C. Controles físicos e ambientais.
   - D. Desenvolvimento de uma política de senha do IAM.

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: C

   </details>

---

**27. Qual serviço da AWS permite que empresas conectem uma VPC da Amazon a um data center local? (Selecione DUAS.)**
   - A. AWS VPN
   - B. Amazon Redshift
   - C. API Gateway
   - D. Amazon Direct Connect

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: A, D

   </details>

---

**28. Uma empresa deseja reduzir a presença física de computação usada pelos desenvolvedores para executar código. Qual serviço atenderia a essa necessidade, permitindo arquiteturas serverless?**
   - A. Amazon EC2
   - B. AWS Lambda
   - C. Amazon DynamoDB
   - D. AWS CodeCommit

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: B

   </details>

---

**29. Qual serviço da AWS fornece alertas quando um evento da AWS pode impactar os recursos da empresa?**
   - A. AWS Personal Health Dashboard
   - B. AWS Service Health Dashboard
   - C. AWS Trusted Advisor
   - D. AWS Infrastructure Event Management

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: A

   </details>

---

**30. Quais das seguintes opções são categorias do AWS Trusted Advisor? (Selecione DUAS.)**
   - A. Tolerância a falhas
   - B. Uso de instâncias
   - C. Infraestrutura
   - D. Desempenho
   - E. Capacidade de armazenamento

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: A, D

   </details>

---

**31. Qual dos seguintes serviços é responsabilidade do cliente manter a configuração do sistema operacional, aplicação de patches de segurança e redes?**
   - A. Amazon RDS
   - B. Amazon EC2
   - C. Amazon ElastiCache
   - D. AWS Fargate

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: B

   </details>

---

**32. Uma empresa estará migrando de um data center local para a AWS Cloud. Qual seria uma diferença financeira após a mudança?**
   - A. Mudança de despesa operacional variável (opex) para despesa de capital antecipada (capex).
   - B. Mudança de despesa de capital antecipada (capex) para despesa de capital variável (capex).
   - C. Mudança de despesa de capital antecipada (capex) para despesa operacional variável (opex).
   - D. Eliminação de despesas de capital antecipadas (capex) e eliminação de despesas operacionais variáveis (opex).

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: C

   </details>

---

**33. Como um cliente deve prever os custos futuros para rodar um novo aplicativo web?**
   - A. Amazon Aurora Backtrack
   - B. Alarmes de faturamento do Amazon CloudWatch
   - C. Calculadora Simples Mensal da AWS
   - D. Relatório de Custo e Uso da AWS

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: C

   </details>

---

**34. Qual é o plano de suporte mínimo da AWS que fornece suporte técnico por chamadas telefônicas?**
   - A. Enterprise
   - B. Business
   - C. Developer
   - D. Basic

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: B

   </details>

---

**35. De acordo com o modelo de responsabilidade compartilhada da AWS, qual é a única responsabilidade da AWS?**
   - A. Segurança de aplicativos
   - B. Gerenciamento de localizações de borda (edge locations)
   - C. Gerenciamento de patches
   - D. Dados do lado do cliente

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: B

   </details>

---

**36. Qual recurso do AWS IAM é usado para associar um conjunto de permissões a vários usuários?**
   - A. Autenticação multifator
   - B. Grupos
   - C. Políticas de senha
   - D. Chaves de acesso

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: B

   </details>

---

**37. Quais dos seguintes são benefícios da AWS Cloud? (Selecione DUAS.)**
   - A. Uptime ilimitado
   - B. Elasticidade
   - C. Agilidade
   - D. Colocation
   - E. Despesas de capital

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: B, C

   </details>

---

**38. Qual das seguintes opções um cliente pode usar para habilitar o login único (SSO) no Console AWS?**
   - A. Amazon Connect
   - B. AWS Directory Service
   - C. Amazon Pinpoint
   - D. Amazon Rekognition

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: B

   </details>

---

**39. Quais são as localizações isoladas dentro de uma região da AWS conectadas por redes de baixa latência chamadas?**
   - A. AWS Direct Connects
   - B. Amazon VPCs
   - C. Localizações de borda (edge locations)
   - D. Zonas de Disponibilidade

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: D

   </details>

---

**40. Quais benefícios o programa de conformidade da AWS oferece aos clientes da AWS? (Selecione DUAS.)**
   - A. Verifica que as cargas de trabalho hospedadas são automaticamente compatíveis com os controles dos frameworks de conformidade suportados.
   - B. A AWS é responsável pela manutenção da documentação dos frameworks de conformidade.
   - C. Garante aos clientes que a AWS está mantendo a segurança física e a proteção de dados.
   - D. Garante o uso de frameworks de conformidade usados por outros provedores de nuvem.
   - E. Adota novos frameworks de conformidade conforme se tornem relevantes para as cargas de trabalho dos clientes.

   <details markdown=1><summary markdown="span">Resposta</summary>

   Resposta correta: B, C

   </details>

---

**41. Qual dos seguintes serviços fornece acesso sob demanda a relatórios de conformidade da AWS?**
- A. AWS IAM
- B. AWS Artifact
- C. Amazon GuardDuty
- D. AWS KMS

<details markdown=1><summary markdown="span">Resposta</summary>

**Resposta Correta**: B

**Explicação**:
- O AWS Artifact fornece acesso sob demanda aos relatórios de conformidade da AWS, como os relatórios SOC, PCI e certificados de segurança.

**Referência**: [AWS Artifact](https://aws.amazon.com/artifact/)

</details>

---

**42. Como parte do modelo de responsabilidade compartilhada da AWS, quais dos seguintes controles operacionais os usuários herdam totalmente da AWS?**
- A. Gestão de segurança do data center
- B. Gerenciamento de patches
- C. Gerenciamento de configuração
- D. Gerenciamento de usuários e acessos

<details markdown=1><summary markdown="span">Resposta</summary>

**Resposta Correta**: A

**Explicação**:
- A AWS é responsável pela segurança física e ambiental dos data centers sob o modelo de responsabilidade compartilhada.

**Referência**: [Modelo de responsabilidade compartilhada da AWS](https://aws.amazon.com/compliance/shared-responsibility-model/)

</details>

---

**43. Ao comparar a AWS Cloud com a Propriedade Total de Custos (TCO) de data centers locais, quais despesas devem ser consideradas? (Escolha duas.)**
- A. Desenvolvimento de software
- B. Gerenciamento de projetos
- C. Hardware de armazenamento
- D. Servidores físicos
- E. Licença de software antivírus

<details markdown=1><summary markdown="span">Resposta</summary>

**Resposta Correta**: C, D

**Explicação**:
- Ao migrar para a nuvem, os custos com hardware de armazenamento e servidores físicos não são mais uma responsabilidade do cliente, já que esses recursos são fornecidos pela AWS.

**Referência**: [Calculadora de TCO da AWS](https://aws.amazon.com/tco-calculator/)

</details>

---

**44. Sob o modelo de responsabilidade compartilhada, quais das seguintes tarefas são responsabilidade do cliente? (Escolha duas.)**
- A. Manutenção do hardware subjacente do Amazon EC2
- B. Gerenciamento das listas de controle de acesso da rede VPC
- C. Criptografia de dados em trânsito e em repouso
- D. Substituição de discos rígidos com falha
- E. Implantação de hardware em diferentes Zonas de Disponibilidade

<details markdown=1><summary markdown="span">Resposta</summary>

**Resposta Correta**: B, C

**Explicação**:
- A AWS cuida da manutenção do hardware, enquanto o cliente é responsável por tarefas como a criptografia de dados e o gerenciamento das listas de controle de acesso da VPC.

**Referência**: [Modelo de responsabilidade compartilhada da AWS](https://aws.amazon.com/compliance/shared-responsibility-model/)

</details>

---

**45. Quais cenários representam o conceito de elasticidade na AWS? (Escolha duas.)**
- A. Escalar o número de instâncias do Amazon EC2 com base no tráfego.
- B. Redimensionar instâncias do Amazon RDS à medida que as necessidades de negócios mudam.
- C. Direcionar automaticamente o tráfego para instâncias do Amazon EC2 menos utilizadas.
- D. Usar documentos de conformidade da AWS para acelerar o processo de conformidade.
- E. Ter a capacidade de criar e gerenciar ambientes usando código.

<details markdown=1><summary markdown="span">Resposta</summary>

**Resposta Correta**: A, B

**Explicação**:
- Elasticidade refere-se à capacidade de ajustar automaticamente recursos como instâncias de EC2 ou RDS com base nas mudanças de demanda.

**Referência**: [Elasticidade na AWS](https://aws.amazon.com/what-is-cloud-computing/)

</details>

---

**46. Quando é benéfico para uma empresa usar uma Instância Spot?**
- A. Quando há flexibilidade em quando uma aplicação precisa ser executada.
- B. Quando há cargas de trabalho de missão crítica.
- C. Quando é necessária capacidade dedicada.
- D. Quando uma instância não deve ser interrompida.

<details markdown=1><summary markdown="span">Resposta</summary>

**Resposta Correta**: A

**Explicação**:
- Instâncias Spot são recomendadas quando o aplicativo pode tolerar interrupções e existe flexibilidade no momento de execução, já que essas instâncias podem ser interrompidas se a AWS precisar de capacidade.

**Referência**: [Instâncias Spot na AWS](https://aws.amazon.com/ec2/spot/)

</details>

---

**47. Uma empresa está considerando mover seu data center local para a AWS. Quais fatores devem ser incluídos em uma análise de Propriedade Total de Custos (TCO)? (Escolha duas.)**
- A. Disponibilidade de instâncias Amazon EC2
- B. Consumo de energia do data center
- C. Custos de mão de obra para substituir servidores antigos
- D. Tempo de desenvolvedor de aplicativos
- E. Capacidade do mecanismo de banco de dados

<details markdown=1><summary markdown="span">Resposta</summary>

**Resposta Correta**: B, C

**Explicação**:
- O consumo de energia e os custos de manutenção do hardware são considerados ao calcular o TCO ao migrar para a AWS.

**Referência**: [Calculadora de TCO da AWS](https://aws.amazon.com/tco-calculator/)

</details>

---

**48. Como a AWS cobra pelo AWS Lambda?**
- A. Os usuários oferecem um lance no preço máximo que estão dispostos a pagar por hora.
- B. Os usuários escolhem um período de pagamento antecipado de 1, 3 ou 5 anos.
- C. Os usuários pagam pelo armazenamento permanente necessário em um sistema de arquivos ou em um banco de dados.
- D. Os usuários pagam com base no número de solicitações e nos recursos de computação consumidos.

<details markdown=1><summary markdown="span">Resposta</summary>

**Resposta Correta**: D

**Explicação**:
- O AWS Lambda cobra com base no número de solicitações feitas e no tempo de execução das funções, o que é medido em milissegundos.

**Referência**: [Preços do AWS Lambda](https://aws.amazon.com/lambda/pricing/)

</details>

---

**49. Qual função os grupos de segurança desempenham em relação à segurança de instâncias do Amazon Elastic Compute Cloud (Amazon EC2)?**
- A. Agem como um firewall virtual para a instância do Amazon EC2.
- B. Protegem contas de usuários da AWS com políticas do AWS IAM.
- C. Fornecem proteção contra DDoS com o AWS Shield.
- D. Usam o Amazon CloudFront para proteger a instância do Amazon EC2.

<details markdown=1><summary markdown="span">Resposta</summary>

**Resposta Correta**: A

**Explicação**:
- Grupos de segurança atuam como firewalls que controlam o tráfego de entrada e saída das instâncias do EC2.

**Referência**: [AWS Security Groups](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html)

</details>

---

**50. Qual cenário de recuperação de desastres oferece a menor probabilidade de tempo de inatividade?**
- A. Backup e restauração
- B. Luz piloto
- C. Standby quente
- D. Multi-site ativo-ativo

<details markdown=1><summary markdown="span">Resposta</summary>

**Resposta Correta**: D

**Explicação**:
- O cenário de "Multi-site ativo-ativo" oferece a menor probabilidade de tempo de inatividade, pois as cargas de trabalho estão ativas em vários locais simultaneamente.

**Referência**: [Melhores práticas para recuperação de desastres na AWS](https://aws.amazon.com/whitepapers/)

</details>

