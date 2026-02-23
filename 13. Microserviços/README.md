# 🚨Estudo-de-Microserviços🚨

# Sobre a Disciplina

Introdução à arquitetura de microserviços, com foco em particionamento de serviços, replicação/distribuição, comunicação assíncrona via filas e soluções serverless. Ênfase em práticas para sistemas distribuídos escaláveis, ágeis e resilientes.

# Conceitos chave

- Microserviços = serviços independentes, descentralizados, modelados em domínios de negócio (DDD, bounded contexts)  
- Práticas recomendadas  
  Modele em torno do domínio, descentralize equipes, evite compartilhamento de código/DB, APIs bem projetadas, loose coupling/high cohesion  
- Escalabilidade = horizontal (mais réplicas) ou vertical (mais capacidade), agilidade com equipes pequenas e entregas rápidas  
- Comunicação assíncrona = filas (garantia de entrega: at most/at least/exactly once), event-driven, sagas para transações distribuídas  
- Orquestração vs Coreografia = centralizada (orquestrador) vs descentralizada (eventos)  
- Trade-offs = complexidade vs monolito, consistência eventual (CAP theorem), resiliência (circuit breaker, retry)  
- Domain Driven Design = linguagem ubíqua, event storming para mapear comandos/agregações/boundaries

# Ferramentas iniciais

Docker (containers), Kubernetes (orquestração), RabbitMQ/Kafka (mensagens), Spring Boot/Node.js (serviços), AWS Lambda (serverless)

# Docentes

- Vinicius Soares (Professor Convidado – Head de Tecnologia, entusiasta de Computação Distribuída, experiência em Java, Arquitetura de Sistemas e Nuvem, liderança em SOA/Microsserviços com open-source, conteúdo online, eventos como Devoxx/TDC/Campus Party, empreendedor ajudando +1000 pessoas em TI)  
- Luis Fernando Planella Gonzalez (Professor PUCRS – Doutor em Ciências da Computação pela PUCRS, desenvolvedor/arquiteto Java desde 1999, certificado Sun, entusiasta de software livre)