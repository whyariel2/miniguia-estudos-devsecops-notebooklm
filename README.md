# 🚀 Acelere sua Aprendizagem com IA – NotebookLM

## 📌 Contexto
Este repositório foi desenvolvido como parte da disciplina **"Acelere sua Aprendizagem com IA"**, com o objetivo de explorar o uso do NotebookLM para aprofundamento em **DevOps e Arquitetura Cloud**.

O tema foi escolhido por sua relevância no mercado de tecnologia, especialmente na construção de sistemas escaláveis, resilientes e automatizados.

---

## 🎯 Objetivos de Estudo
- Compreender os princípios de DevOps  
- Estudar arquiteturas modernas em cloud  
- Explorar práticas como CI/CD, containers e infraestrutura como código  
- Utilizar IA para acelerar o aprendizado técnico  

---

## 📚 Curadoria de Fontes

1. AWS Well-Architected Framework  
https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html  

2. Google Cloud Architecture Framework  
https://cloud.google.com/architecture/framework  

3. The DevOps Handbook  
https://itrevolution.com/the-devops-handbook/  

4. Docker Documentation  
https://docs.docker.com/  

5. Kubernetes Documentation  
https://kubernetes.io/docs/

[Ver todos os links](https://github.com/whyariel2/miniguia-estudos-devsecops-notebooklm/blob/main/fontes/links.md)

---

## 🧪 Engenharia de Prompts

### 🔹 Prompt 1 (DevSecOps)
> "Explique o que é devsecops e ferramentas utilizadas como se eu fosse um iniciante e depois aprofunde para um nível mais avançado"

---

### 📌 Resposta obtida

> O DevSecOps é a evolução do DevOps que integra a segurança como uma parte essencial e contínua de todo o ciclo de vida de desenvolvimento de software. Em vez de tratar a segurança como uma etapa final de revisão, ela é incorporada desde o início, promovendo uma propriedade compartilhada da segurança entre as equipes de desenvolvimento, operações e segurança.
> 
> **Nível Iniciante: O que é e ferramentas básicas**
> 
> Para um iniciante, imagine que o desenvolvimento de um software é como construir uma casa. No modelo antigo, o inspetor de segurança só aparecia quando a casa estava pronta; se houvesse um erro na fundação, a obra teria que ser destruída. No DevSecOps, o inspetor está presente em cada tijolo colocado.
> **Principais ferramentas para quem está começando:**
> - **Controle de Versão (Version Control):** Onde o código é guardado com segurança. Exemplos: **Git**, **GitHub** e **AWS CodeCommit**.
> - **Integração e Entrega Contínua (CI/CD):** Ferramentas que automatizam o processo de testar e lançar o código assim que ele é alterado. Exemplos: **AWS CodePipeline** e **Cloud Build (Google Cloud)**.
> - **Infraestrutura como Código (IaC):** Permite criar servidores e redes usando apenas arquivos de texto (modelos), garantindo que o ambiente seja sempre o mesmo e seguro. Exemplos: **AWS CloudFormation** e **Terraform**.
> - **Containers:** Caixas virtuais que garantem que o software rode da mesma forma em qualquer lugar. Exemplo: **Docker**.
>
> --------------------------------------------------------------------------------
> **Nível Avançado: Práticas e Arquitetura**
> 
> Em um nível mais profundo, o DevSecOps foca no conceito de **"Shift-Left Security"** (deslocar a segurança para a esquerda), o que significa realizar testes e validações de segurança o mais cedo possível no ciclo de desenvolvimento.
> 1. **Política como Código e Governança**
>
>    Práticas avançadas utilizam a **Política como Código** para automatizar a conformidade. O **AWS Config**, por exemplo, permite criar regras que verificam automaticamente se as configurações dos recursos estão seguras e em conformidade com as normas da empresa. Se um recurso for criado fora dos padrões, o sistema pode enviar notificações ou até mesmo realizar uma **correção automática**.
> 2. **Proteção de Infraestrutura e Gestão de Vulnerabilidades**
>
>     A segurança avançada exige o gerenciamento rigoroso de vulnerabilidades em todas as camadas:
>    - **Imagens Blindadas (Hardened Images):** Uso de imagens de sistemas operacionais pré-configuradas com o mínimo de serviços necessários para reduzir a superfície de ataque.
>    - **Gestão de Patching:** Uso de sistemas como o AWS Systems Manager para aplicar atualizações de segurança automaticamente em milhares de instâncias, evitando brechas conhecidas.
>    - **Autorização Binária:** No Google Cloud, ferramentas como a **Binary Authorization** garantem que apenas imagens de containers que foram testadas e aprovadas em processos de CI/CD possam ser executadas em produção.
> 3. **Identidade e Gestão de Acessos (IAM)**
>
>     A segurança avançada aplica o **Princípio do Menor Privilégio**, garantindo que pessoas e máquinas tenham apenas as permissões estritamente necessárias para suas tarefas. Isso inclui o uso de **credenciais temporárias** em vez de chaves de acesso fixas, além de auditorias periódicas e rotação de segredos.
> 4. **Observabilidade e Auditoria**
>
>     Para detectar eventos de segurança em tempo real, o DevSecOps avançado utiliza:
>    - **Rastreamento Distribuído:** Ferramentas como **AWS X-Ray** ajudam a analisar como os dados fluem em arquiteturas complexas de microserviços, identificando comportamentos anômalos.
>    - **Logs de Auditoria:** O **AWS CloudTrail** registra todas as chamadas de API feitas na conta, permitindo rastrear quem fez o quê, quando e de onde, o que é fundamental para a resposta a incidentes e investigações forenses.
>    - **Detecção de Ameaças com ML:** Serviços como o **Amazon DevOps Guru** utilizam aprendizado de máquina para detectar comportamentos anormais antes que eles causem impactos reais aos clientes.

---

### 📊 Análise do Prompt

#### ✅ Pontos fortes:
- Estrutura em níveis (iniciante e avançado)  
- Uso de analogia facilitou entendimento  
- Inclusão de ferramentas reais do mercado  

#### ⚠️ Pontos de melhoria:
- Poderia incluir exemplos reais de empresas  
- Poderia detalhar um fluxo DevSecOps completo (pipeline)

---

### 🔧 Prompt Melhorado
> "Explique DevSecOps com analogia simples, depois detalhe a arquitetura completa incluindo pipeline CI/CD com segurança integrada e exemplos reais de empresas."

---

## ⚠️ Dificuldades (Cicatrizes)
- Respostas iniciais muito genéricas  
- Necessidade de prompts mais específicos  
- Falta de exemplos práticos em algumas respostas  

---

### 🔹 Prompt 2:
> "O que é o TOP 10 OWASP e por que é tão importante saber sobre ele quando se trabalha com DevSecOps?"

📌 Resultado:
> O OWASP Top 10 é um documento de conscientização padrão para desenvolvedores e segurança de aplicativos, representando um consenso sobre os riscos de segurança mais críticos para aplicações web. No contexto de nuvem, como o Google Cloud, ele serve como uma base para definir opções de mitigação e proteção contra ameaças comuns.
> Saber sobre o OWASP Top 10 é fundamental para quem trabalha com DevSecOps pelos seguintes motivos:
> - Implementação do "Shift-Left Security": O DevSecOps promove a integração da segurança desde as fases iniciais do projeto. Conhecer as vulnerabilidades do Top 10 permite que as equipes identifiquem riscos já na fase de design e codificação, evitando que falhas críticas cheguem à produção.
> - Treinamento em Segurança de Aplicativos (SEC11-BP01): O Framework de Arquitetura recomenda treinar as equipes de carga de trabalho para reconhecer e mitigar propriedades de segurança, sendo o OWASP uma das referências principais para esse conhecimento técnico.
> - Automação de Testes (SEC11-BP02): No pipeline de CI/CD, o DevSecOps utiliza ferramentas para automatizar testes de segurança. Essas ferramentas são frequentemente configuradas para escanear o código em busca das falhas listadas no OWASP Top 10, garantindo uma validação contínua durante o ciclo de vida de liberação.
> - Padronização e Documentação: Uma arquitetura bem documentada estabelece uma linguagem comum entre as equipes de desenvolvimento, operações e segurança. O OWASP Top 10 fornece esse vocabulário padrão, ajudando a priorizar mitigações usando modelos de ameaças (SEC01-BP07).
> - Conformidade e Governança: O uso de diretrizes como as do OWASP auxilia na criação de guardrails de permissão e políticas de configuração automática (como no AWS Config), garantindo que a infraestrutura e a aplicação permaneçam seguras e em conformidade com as melhores práticas da indústria.
> 
> Em resumo, o OWASP Top 10 fornece o roteiro necessário para que as práticas de automação, monitoramento e resposta a incidentes do DevSecOps sejam direcionadas para as vulnerabilidades que representam o maior risco real para o negócio.

---

### 📊 Análise do Prompt

#### ✅ Pontos fortes:
- Resposta objetiva e aplicada ao contexto DevSecOps  
- Boa conexão com práticas reais (CI/CD, governança)  

#### ⚠️ Melhorias:
- Não detalha exemplos de vulnerabilidades  
- Poderia incluir casos reais de ataques  

#### 🔧 Prompt Melhorado:
> "Explique cada vulnerabilidade do OWASP Top 10 com exemplos reais de ataques e como mitigá-las em um pipeline DevSecOps."

---

## ⚠️ Dificuldades (Cicatrizes)
- Respostas iniciais genéricas  
- Necessidade de maior especificidade nos prompts  
- Falta de exemplos práticos em algumas respostas  

---

## 📖 Resumo

### 🔹 DevOps
Integra desenvolvimento e operações com foco em automação e entrega contínua.

### 🔹 DevSecOps
Integra segurança em todas as etapas do desenvolvimento.

### 🔹 OWASP Top 10
Lista das vulnerabilidades mais críticas em aplicações web.

### 🔹 CI/CD
Pipeline automatizado de build, teste e deploy.

---

## 📚 Glossário

- **DevSecOps** → Segurança integrada ao DevOps  
- **OWASP Top 10** → Principais riscos de segurança web  
- **CI/CD** → Pipeline automatizado  
- **IAM** → Controle de acesso  
- **Shift-Left Security** → Segurança desde o início  

---

## 🔁 Prompts Reutilizáveis

### 📌 Para aprendizado
- "Explique [conceito] de forma simples e depois avançada"
- "Explique com analogias do mundo real"

---

### 📌 Para prática
- "Como implementar [tecnologia] passo a passo?"
- "Quais ferramentas são usadas com [tecnologia]?"

---

### 📌 Para aprofundamento
- "Quais erros comuns ao usar [tecnologia]?"
- "Compare [tecnologia A] vs [tecnologia B]"

---

### 📌 Para revisão
- "Resuma este conteúdo em tópicos"
- "Crie um checklist sobre [tema]"
