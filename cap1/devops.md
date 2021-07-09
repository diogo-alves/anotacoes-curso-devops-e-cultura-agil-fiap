## O que é DevOps?

É uma cultura organizacional que integra desenvolvedores (Dev) e sysadmins (Ops) com o objetivo de automatizar processos, visando garantir uma maior velocidade nas entregas de software sem abrir mão da estabilidade.


## Funcionamento do DevOps

A adoção da cultura de DevOps não significa que o desenvolvedor precisa conhecer a fundo todas as rotinas de um sysadmin e vice e versa, mas é interessante que cada um saiba ao menos o essencial sobre a rotina do outro. Essa interação resulta em um maior conhecimento sobre as dificuldades e melhorias necessárias durante o desenvolvimento e entrega de software, garantindo mais autonomia aos membros da equipe.


## Benefícios do DevOps

*   Entregas mais rápidas: os processos passam a ser automatizados;
*   Escalabilidade: possibilidade de monitorar e escalar sua infraestrutura de forma automática, conforme a necessidade;
*   Agilidade: todos da equipe entendem do início ao fim cada etapa do desenvolvimento e entrega do software, reduzindo bloqueios;
*   Colaboração contínua: desenvolvedores e sysadmins passam a ter a mesma visão sobre o produto, evitando processos ineficazes;
*   Confiabilidade: o controle de qualidade do software é feito automaticamente em todas suas etapas, através de diferentes testes;
*   Segurança: alcançada com o emprego de políticas de controle de acesso bem definidas e automatizadas.


## Práticas de DevOps

*   Inplantação de metodologias ágeis, como SCRUM e KANBAN: garantem a realização de atualizações frequentes no software;
*   Infraestrutura como Código (IaC): permite automatizar por meio de código rotinas de infraestrutura, como deploys, load balancers, etc;
*   Microserviços: têm por objetivo desacoplar funcionalidades de um sistema complexo. Isso leva a uma melhor manutenção e escalabilidade de cada serviço;
*   Integração Contínua (CI): permite realizar testes no código sempre que uma alteração é enviada ao repositório central, garantindo agilidade na correção de erros e maior qualidade do produto desenvolvido;
*   Entrega contínua (CD): etapa que visa validar todas as etapas do desenvolvimento do software, com o objetivo de garantir que tudo esteja pronto para o deploy; 
*   Monitoração, alarme, log e indexação: é a melhor maneira de rastrear problemas e prover soluções. Indexando os logs é possível acompanhar a saúde do software em tempo real, sendo possível até programar alarmes caso ocorram determinadas situações críticas;
*   Comunicação e colaboração: o compartilhamento de experiências entre as equipes garante que todos possam trabalhar juntos em prol de um objetivo em comum, fortalecendo a cultura de colaboração na organização.



## Estágios e ferramentas DevOps

![estágios e ferramentas](https://i.imgur.com/9k0MDzb.png)

1.   Planejamento (plain): fase onde são definidas as atividades e suas estimativas de entrega;
2.   Desenvolvimento (code): nesta etapa ocorre o início da codificação do software e os ajustes para a automação da infraestrutura.
3.   Construção (build): etapa onde o projeto é compilado e empacotado, estando pronto para os testes.
4.   Testes (test): etapa em que tanto testes de software quanto de automação da infraestrutura são realizados;
5.   Lançamento (release): todo o processo é automatizado por meio de um pipeline de entrega, que pode incluir etapas desde a execução de testes até a aprovação da release pelo usuário responsável;
6.   Implantação (deploy): faz parte do pipeline de entrega e é responsável pela instalação do software desenvolvido e da infraestrutura. Todo o processo é automatizado por meio de ferramentas como o docker;
7.   Operação (operate): promove modificações na infraestrutura, desde uma simples manutenção até seu redimensionamento;
8.   Monitoração (monitor): realiza o acompanhamento do ambiente em tempo real, analisando a performance, o comportamento do software, dos usuários, etc.


## DevSecOps

Por vezes a segurança é uma área negligenciada, só recebendo a devida atenção após a entrega do software ou quando ocorre um incidente, como um vazamento de dados, por exemplo. 

Hoje em dia já existe um movimento no mercado incentivando que o cuidado com a segurança esteja presente desde o início do ciclo de desenvolvimento. Isso pode ser alcançado através da criação de uma estratégia de segurança, mas requer a cooperação de todos os envolvidos e necessita da automação de certos aspectos do processo.