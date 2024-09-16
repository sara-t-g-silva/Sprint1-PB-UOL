# **Compass.uol**

# Avaliação Sprint 1 – Programa de Bolsas

# Estagiário(a): Sara Thaíse 

#### **Tema: Segurança de redes: Conheça as vulnerabilidades de servidores e clientes**

01. **O que é um ataque DDoS e como posso me proteger?**

- ##### Ataque de negação de serviço distribuído, ou no inglês Distributed Denial of Service. Este ataque acontece quando o hacker sequestra máquinas de usuários para o seu exército, isto é feito através de vírus ou malwares. Este tipo de  ataque consome todas as conexões do servidor, assim quando o cliente solicita um serviço, esse serviço é negado, porque foi totalmente consumido pelo ataque hacker.  Para se proteger dos ataques não existe formulas mirabulantes, algumas dicas são: utilizar firewalls para gerenciar suas conexões, investir em largura de banda, bot's de cadastro, vários servidores de acesso. 

02. **Por que o firewall é uma ferramenta muito importante de proteção?**
- ##### O firewall é usado para impedir ataques, ele divide a rede segura da rede não segura, podendo assim controlar o tráfego de dados permitindo ou negando entre rede interna e rede externa, esse processo é feito através da memória statefull que consegue guardar informações de requisições internas que foram iniciadas. No geral, o usuário que está na rede interna pode acessar recursos da rede externa e o caminho inverso não é permitido por conta do firewall, que bloqueia o acesso a rede vindo de fora.

#### **Tema: Git e GitHub** 

03. **Explique de forma sucinta, o fluxo e envio de um arquivo novo para o repositório do projeto.**
- ##### pode-se iniciar a pasta diretamente no git bash, utilizando o botão direito do mouse, começando a utilizar os comandos a partir do passo 2. A segunda maneira é abrindo o terminal git bash e realizando os comandos a seguir:

1. ##### ``` cd ../Documents/projeto1 ``` - este comando irá abrir a pasta no terminal git bash
2. ##### ```git init``` - realizará a iniciação de um repositório no diretório
3. ##### ```git status``` - verifica o estado do seu diretório
4. #####  ```git add <nome do arquivo>``` - adiciona as alterações do arquivo e começa a monitorar
5. ##### ```git commit –m “<descrição>”``` - captura o estado atual do arquivo e adiciona as alterações para o histórico do repositório local atribuindo um hash como identificação, com o “–m” podemos adicionar uma descrição das mudanças realizadas.
6. ##### ```git remote add origin <endereço/caminho>``` -é utilizado para gerenciar os repositórios monitorados, é para onde os repositórios serão push
7. ##### ```git push -u origin master``` -utilizado para enviar as mudanças commitadas.

04. **Descreva sobre os ganhos de se utilizar a funcionalidade da branch do git.**
- #### É possível trabalhar em equipe de forma coordenada, onde cada desenvolvedor tem a possibilidade de trabalhar em features sem que modifique a branch main de desenvolvimento, evitando conflitos de desenvolvimentos, no final de suas features pode ser feito um marge para a main.

05. **Explique a diferença entre criar o repositório na nuvem e iniciar o repositório a partir de um código existente local.**

- ##### Quando se inicia um repositório em nuvem, por clonagem, automaticamente é criada uma conexão remota chamada origin por padrão do GitHub, o que difere de iniciar esse repositório de um código existente local, esta abordagem é feita de forma manual.

06. **Qual a diferença entre Git e GitHub?**
- ##### O Git é um sistema de controle de versão distribuído de software livre e de código aberto projetado para gerenciar todo o histórico de código-fonte.  

- ##### O GitHub é um serviço de hospedagem baseado na web para repositórios Git. 

#### **Tema: Fundamentos de Agilidade: seus primeiros passos para a transformação ágil** 

07. **Quais as principais diferenças entre o modelo ágil e o waterfall (modelo em cascata)?**
- ##### Metodologia Waterfall – Também conhecida como cascata, o desenvolvimento é feito de forma linear, com várias etapas pré-definidas, uma após a outra.
- ##### Etapas do modelo Walterfall:
1. ##### concepção
2. ##### Iiniciação
3. ##### Análise
4. ##### Design
5. ##### Codificação
6. ##### Teste
7. ##### Implementação
8. ##### Manutenção

- ##### Metodologia Agile – é oposta ao waterfall, o objetivo é dar flexibilidade para o desenvolvimento de uma solução e possibilitar que mudanças ocorram durante o processo.
- ##### Principais diferenças entre metodologia ágil e waterfall:
1. ##### A priorização
2. ##### Fluxos de tarefas
3. ##### Feedback


08. **Quais são as 3 perguntas que devem ser respondidas na Daily?**
- ##### O que você fez até aqui?
- ##### O que pretende fazer até a próxima Daily?
- ##### Teve algum impedimento?

09. **Qual o intuito das seguintes cerimônias?**
- **Daily** - reunião diária com no máximo 15 min para verificar o andamento do projeto, é feita com toda a equipe se possível.
- **Planning** - é o momento que se inicia a sprint, se limita a 5% da sprint, é o processo de planejamento da sprint, P.O. chega na reunião com o produtc backlog. 
- **Refinamento** - É nesta reunião que o P.O. refina o topo do product Backlog.
- **Review** - é o momento no qual o cliente e o time de desenvolvimento se reúnem para mostrar os incrementos feitos na sprint. É um time-box, não pode ultrapassar de 2,5% do tempo total da sprint, é quando se faz entregas ao cliente, algo "pronto".
- **Retrospectiva** - É a maior oportunidade, em cada sprint, de promoção de melhorias no processo, no time e no andamento do projeto que está sendo desenvolvido.

10. **O que é a estimativa na metodologia ágil?**
- ##### é para se obter uma ideia dos custos e esforços envolvidos no projeto. É de grande ajuda para decisão de que o trabalho pode ou não ser realizado

#### **Tema: Fundamentos HTTP**

11. **O que é o protocolo HTTP? Qual a diferença entre HTTP e HTTPS?**
- ##### HiperText Transfer Protocol (HTTP), é o protocolo que define as regras de comunicação na web. O HTTPs usa criptografia baseada em chaves públicas e privadas, diferente do HTTP, que não se faz uso de cripitografia para a comunicação.


 12. **Cite 4 métodos HTTP.**
 - ##### GET
 - ##### POST
 - ##### DELETE
 - ##### PUT