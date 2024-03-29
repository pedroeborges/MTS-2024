## A importância do hardening para a proteção de workloads na AWS

**Pilares da segurança da informação:**

A implementação da segurança da informação é baseada em 3 pilares fundamentais:  
 - Pessoas 
 - Processos 
 - Tecnologia 

É de suma importância que haja equilíbrio entre eles, para que um plano de segurança seja eficaz. 

O *[hardening](Hardening.md)* é um dos processos que é muito útil a tarefa de identificação de falhas e implementação de medidas de segurança.  

**Conceito de *hardening***:
É o processo de fortalecer sistemas, redes, softwares, infraestruturas de TI contra ciberataques, minimizando ameaças a um alvo específico, por meio de redução de vulnerabilidades e ampliação de medidas defensivas.
É parte essencial de um plano de continuidade de negócios. 

Uma das contramedidas do processo é a redução da superfície de ataque existente, minimizando as chances de uma ataque ser bem sucedido. 

**Ações relacionadas:** 
 - Excluir contas não utilizadas 
 - Rever permissões e pontos de acesso 
 - Desativar serviços desnecessários/não utilizados 
 - Mapear vulnerabilidades
 
 Apesar da sua importância, o processo ainda é muito pouco utilizado. Segundo pesquisa da [ServiceNow](https://www.servicenow.com/content/dam/servicenow-assets/public/en-us/doc-type/resource-center/infographic/info-security-hygiene.pdf):
 -  73% utilizam planilhas como fator chave de S.I
 - 57% nãos sabem quais ativos são críticos para o negócio

 **Pilares para aplicação:**
  - Princípio de privilégio mínimo 
	   - Conceder apenas os privilégios necessários para desempenho da função de casa usuário 
	   - Reduz o números de formas potenciais de acesso indevido ao sistema 
	   - Medida de profundidade deve ser utilizada em conjunto com outros controles de segurança  
 - Segmentação 
	 -  A utilização de containers proporciona camada adicional de segurança ao isolar aplicações de outros serviços 
 - Redução 
	 -  Reduzir serviços que não sejam necessários à operação 
	 - Analisar o propósito de cada serviços, e identificar quais são necessários e quais podem ser desativados com segurança  
 
 **Boa práticas:**
 
 O  *hardening* deve ser incorporado a cultura de segurança da informação da organização. Portanto, é necessário capacitar e conscientizar as equipes que irão executar o processo. 
 
 É de suma importância entender as ameaças que enfrentadas pela organização e suas aplicações, para priorizar os esforços e assegurar que as áreas mais vulneráveis seja protegidas primeiro. 

O *hardening* deve ser aplicado em camadas, para aumento do nível de segurança  

O processo deve ser constantemente monitorado e atualizado com base nas novas ameaças. 

**Utilizando *benchmarks* do CIS Security** 

O [CIS](https://www.cisecurity.org/) (*Center for Internet Security*) é uma organização sem fins lucrativos, que desenvolve *benchmarks*, composto de um conjunto de práticas recomendadas para proteger configurações de um sistema. 

As diretrizes do CIS são reconhecidas por muitos padrões de conformidade, como referência para a criação de uma políticas de *hardening*.

Os padrões  do CIS cobrem uma ampla gama de tópicos, incluindo gerenciamento de senhas, firewalls e detecção de intrusão. São atualizados regularmente para refletir atualizações nas tecnologias e combater novas ameaças. 
 
 **Etapas de implementação:** 
 - Avaliação do ecossistema
 - Automatização 
  -- IAC
  -- Aplicação de patches 
  
**Links úteis:**
[ISO 27001](https://www.27001.pt/)
[CIS Security](https://www.cisecurity.org/)

