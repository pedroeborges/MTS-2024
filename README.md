## A importância do hardening para a proteção de workloads na AWS

**Pilares da segurança da informação:**

A implementação da segurança da informação é baseada em 3 pilares fundamentais:  
 - Pessoas 
 - Processos 
 - Tecnologia 

É de suma importância que haja equilíbrio entre eles, para que um plano de segurança seja eficaz. 

O *[hardening](docs/Hardening.md)* é um dos processos que é muito útil a tarefa de identificação de falhas e implementação de medidas de segurança.

**Ferramentas para análise de vulnerabilidades e validação de ajustes**

- **Prowler Cloud**
  - Ferramenta de código aberto multicloud, quer permite avaliar e auditar contas quanto à adesão às melhores práticas de segurança, apresentando resultados em dashboards intuitivos e apresentando recomentações para realização de ajustes.
  - Documentação: https://docs.prowler.com/projects/prowler-open-source/en/latest/
  - Download: https://github.com/prowler-cloud/prowler

- **Cloudsplaing**
  - Ferramenta de código aberto que identifica violação de privilégios em políticas IAM da AWS, através da geração de relatóriso em HLTM apresentando falhas de segurança identificadas e sugestões para correção. É possível realizar a análise de todas políticas de uma conta ou um política específica.  
  - Documentação: https://cloudsplaining.readthedocs.io/en/latest/
  - Download: https://github.com/salesforce/cloudsplaining

- **Quiet Riot**
  - Ferramenta que permite enumeração não autenticada de serviços, roles e usuários e contas AWS, Azure e GCP, utilizando estas informações para análise de vulnerabilidades e falhas de segurança. A ferramenta conta conta vários recursos como deflagação de ataques de brute force baseados em dicionários e técnicas de elevação de privilégios.
  - Documentação:
    - https://medium.com/@wsladd/quiet-riot-a-defenders-perspective-5c569185effc    - 
  - Download: https://github.com/righteousgambit/quiet-riot?tab=readme-ov-file  


