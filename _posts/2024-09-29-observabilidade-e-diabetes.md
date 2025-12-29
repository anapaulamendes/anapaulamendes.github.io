---
layout: post
title: Observabilidade aplicada à Diabetes
date: 2024-09-29 10:00:00
categories:
- Observability
---


### Da saúde de aplicações à saúde humana: Como a observabilidade aplicada ao monitoramento de glicemia ajuda pessoas diabéticas

### 1. Introdução

A observabilidade é um conceito essencial na administração de sistemas, composto por quatro pilares principais: monitoramento, métricas, logs e alertas. Esses elementos permitem uma análise detalhada de eventos e comportamento de sistemas em tempo real, facilitando a detecção de anomalias, diagnósticos rápidos e intervenções proativas. O monitoramento rastreia a saúde e o desempenho contínuo do sistema, as métricas fornecem dados quantitativos para avaliação, os logs registram eventos históricos e os alertas notificam quando algo foge dos parâmetros normais.

Assim como esses princípios se aplicam a sistemas computacionais, eles também podem ser usados na área da saúde, especialmente no contexto do monitoramento de doenças crônicas como a diabetes. O Sensor Libre 2 é um exemplo dessa interseção, sendo um dispositivo de monitoramento contínuo de glicemia que aplica os conceitos de observabilidade para ajudar pessoas diabéticas a manter um controle eficaz e em tempo real de seus níveis de glicose. Ele coleta dados contínuos, gera alertas quando os níveis estão fora do padrão e armazena logs para acompanhamento médico e ajuste de tratamentos.


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/0c0dze4jhge6i5dqdkty.png)


O Sensor Libre 2 é um dispositivo de monitoramento contínuo de glicemia projetado para ajudar pessoas com diabetes a controlar seus níveis de glicose de maneira mais eficiente e prática. Ao contrário dos métodos tradicionais, como as picadas no dedo para medir a glicemia, o Sensor Libre 2 oferece monitoramento contínuo e em tempo real, proporcionando uma visão mais ampla e detalhada do comportamento da glicemia ao longo do dia.

A diabetes é uma condição crônica caracterizada pela incapacidade do corpo de regular adequadamente os níveis de glicose no sangue. Isso ocorre devido à produção insuficiente de insulina (diabetes tipo 1) ou à resistência das células à insulina (diabetes tipo 2), o hormônio responsável por ajudar a glicose a entrar nas células para ser usada como energia. Quando não controlada, a diabetes pode levar a complicações graves, como doenças cardíacas, danos nos nervos, problemas renais e perda de visão. O controle contínuo dos níveis de glicose é essencial para prevenir essas complicações e manter a qualidade de vida. É nesse contexto que dispositivos como o Sensor Libre 2 desempenham um papel crucial no monitoramento proativo da glicemia.

A partir do feedback constante dos níveis de glicose no sangue, o Sensor Libre 2 ajuda as pessoas com diabetes a tomar decisões em tempo real sobre alimentação, aplicação de insulina e realização de atividades físicas. A comparação com os pilares da observabilidade evidencia no monitoramento contínuo, métricas precisas, logs históricos das leituras de glicose e alertas proativos no qual criam uma infraestrutura que permite o gerenciamento otimizado da saúde.

### 2. Monitoramento: Acompanhamento Contínuo

O monitoramento é uma prática essencial no gerenciamento de sistemas, consistindo no processo de observar e coletar dados sobre o comportamento e o desempenho de uma aplicação, infraestrutura ou serviço ao longo do tempo. Ele permite que equipes técnicas acompanhem continuamente o estado dos sistemas, identifiquem problemas potenciais e tomem decisões informadas com base nos dados coletados. O objetivo do monitoramento é garantir que o sistema esteja operando conforme esperado, fornecendo insights que possibilitam a detecção e correção de falhas antes que elas afetem os usuários finais.

O monitoramento coleta informações em tempo real sobre diversos aspectos do sistema, como uso de CPU, memória, tráfego de rede, taxa de erros e disponibilidade. Essas informações são frequentemente apresentadas em dashboards e ajudam a identificar padrões que indicam problemas de desempenho ou falhas iminentes. Quando configurado corretamente, o monitoramento também pode incluir alertas automáticos que notificam os administradores quando certos parâmetros ultrapassam limites críticos, permitindo uma resposta rápida.

De acordo com o Google Site Reliability Engineering Handbook, o monitoramento é crucial para manter a confiabilidade e o desempenho de sistemas complexos, especialmente em ambientes distribuídos, onde as falhas podem ocorrer em vários pontos da infraestrutura . Além disso, o monitoramento contínuo permite a coleta de dados históricos, que podem ser usados para realizar análises preditivas e identificar áreas de melhoria no desempenho do sistema.

O Sensor Libre 2 realiza o monitoramento contínuo da glicemia através de um pequeno sensor que é aplicado na pele, geralmente na parte superior do braço. Esse sensor mede os níveis de glicose no líquido intersticial (o fluido entre as células da pele), o que elimina a necessidade de picadas no dedo para obter as leituras.

O sensor mede continuamente os níveis de glicose no líquido intersticial a cada minuto. Ele armazena essas leituras internamente e as transmite via tecnologia de comunicação sem fio (Bluetooth) para um leitor dedicado ou para um aplicativo de smartphone.

Além das leituras em tempo real, o sensor armazena até 8 horas de dados contínuos, permitindo que o usuário e seu médico analisem tendências e padrões no comportamento da glicemia. Esses dados podem ser visualizados como gráficos no aplicativo, fornecendo uma visão clara das flutuações de glicemia ao longo do dia.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/nhmja1wyydim7dc9san5.jpg)

### 3. Métricas: Dados Quantificáveis

Métricas são um dos pilares fundamentais da observabilidade, proporcionando uma visão quantitativa do comportamento e do desempenho de sistemas. Elas consistem em dados numéricos que refletem o estado de diferentes componentes, permitindo monitorar indicadores chave, como uso de CPU, tempo de resposta de aplicações, taxas de erro e latência de rede. Ao transformar eventos em números, as métricas tornam possível quantificar o desempenho e detectar padrões anômalos, facilitando uma intervenção rápida.

No contexto da observabilidade, as métricas desempenham um papel crucial ao ajudar equipes técnicas a entenderem como o sistema está se comportando ao longo do tempo. Elas oferecem uma visão geral que permite identificar tendências, gargalos e problemas de desempenho de maneira eficiente. Por exemplo, um aumento na latência pode indicar sobrecarga de tráfego, enquanto uma queda repentina nas taxas de solicitação pode ser um sinal de falha em um serviço. Com métricas em tempo real, é possível não só reagir a incidentes rapidamente, mas também prever problemas futuros por meio da análise de dados históricos.

Além disso, as métricas possibilitam uma abordagem mais proativa na gestão de sistemas, permitindo a criação de alertas baseados em limites predefinidos. Quando uma métrica atinge um valor crítico, o sistema pode disparar notificações automáticas para que os administradores tomem as medidas necessárias antes que ocorra uma falha maior. Essa capacidade de monitorar constantemente, quantificar o desempenho e gerar insights acionáveis torna as métricas indispensáveis para a manutenção de um ambiente estável e otimizado.

O Sensor Libre 2 captura uma série de métricas relacionadas aos níveis de glicemia, fornecendo informações valiosas para o controle diário do diabetes e auxiliando nas decisões de tratamento. As principais métricas capturadas pelo dispositivo incluem:

-   Padrões Diários: O Sensor Libre 2 apresenta a distribuição dos níveis de glicemia ao longo de um período de tempo. Isso pode ser mostrado como um histograma, indicando a frequência com que os níveis de glicose ficaram dentro de certas faixas (baixa, normal, alta). Essa distribuição ajuda a identificar se os níveis de glicose estão passando mais tempo fora da faixa ideal e se ajustes no tratamento são necessários.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/70mx7yvize1nyg3cp0lu.jpg)

-   Tempo no Alvo: O "tempo no alvo" refere-se à porcentagem de tempo em que os níveis de glicemia permanecem dentro de uma faixa saudável predefinida. Esta métrica é essencial para avaliar a eficácia do tratamento e o quanto o controle da glicemia está sendo mantido. Um tempo no alvo elevado está associado a melhor controle do diabetes e menor risco de complicações.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/xne20pqwelcg54vx8sd6.jpg)

-   Eventos de Hipoglicemia (Glicose baixa no sangue): O sensor registra episódios de hipoglicemia (glicose baixa). Com esses dados em mãos, os pacientes podem entender melhor como seus corpos reagem a diversos fatores, ajudando a manter os níveis de glicose mais estáveis e seguros.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/2vvajq5mwvor2mydj0wn.jpg)


-   Média da Glicemia: O Sensor Libre 2 calcula a média das medições de glicose, fornecendo uma visão geral de como o controle da glicemia está sendo mantido ao longo do tempo. A partir dessa média, é possível estimar o  A1c (glicada estimada), um indicador de longo prazo do controle glicêmico.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ew94tvj5r2j9c6ftpcfi.jpg)

-   Gráfico Diário: O gráfico diário do Sensor Libre 2 é uma visualização essencial para acompanhar os níveis de glicemia ao longo do dia. Ele exibe as leituras contínuas de glicose capturadas pelo sensor em intervalos regulares, permitindo uma análise clara de como os níveis de glicose variam em diferentes momentos, como após refeições, exercícios, períodos de jejum, e até durante o sono.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4ifjnmm9o4los4a9gbpx.jpg)

-   A1c Estimado (Hemoglobina Glicada): O estimated A1c ou HbA1c estimado, é uma estimativa do valor da hemoglobina glicada com base nos níveis médios de glicose registrados ao longo de um período. O HbA1c é um exame laboratorial que mede a quantidade de glicose que se liga à hemoglobina no sangue, e fornece uma visão do controle glicêmico de uma pessoa nos últimos 2 a 3 meses. Já o A1c é estimado a partir de dados de glicemia contínuos coletados por sensores. Ele oferece uma estimativa do valor de HbA1c com base nas medições diárias, mas pode ter pequenas variações em relação ao exame laboratorial. Embora não seja um substituto exato do teste laboratorial, o A1c oferece uma estimativa útil para avaliar o controle da diabetes no dia a dia.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ejg85kdntutbbv3yt28s.jpg)

-   Uso do sensor: É uma medida importante para garantir que o Sensor Libre 2 está sendo utilizado corretamente e com frequência suficiente para fornecer leituras confiáveis e contínuas dos níveis de glicose. Essa métrica reflete a frequência com que o sensor é escaneado para captar os dados e pode indicar se o paciente está realizando o monitoramento adequado da glicose.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/yh1yh2z0vatrsn2t84hr.jpg)

### 4. Logs: Histórico de Eventos

Os logs são registros detalhados das atividades e eventos que ocorrem em um sistema, essenciais para o diagnóstico de problemas e para a observabilidade. Eles fornecem informações sobre o comportamento do sistema ao longo do tempo, capturando dados sobre erros, eventos importantes, desempenho, e ações executadas pelos usuários. Em sistemas complexos, como aplicativos de software ou plataformas de monitoramento, os logs são a principal ferramenta para identificar falhas, rastrear a origem de problemas e garantir que o sistema esteja funcionando conforme esperado.

Importância dos logs no diagnóstico de problemas:

-   Rastreabilidade: Os logs oferecem um histórico detalhado de todas as ações realizadas dentro do sistema. Isso permite que os administradores de sistemas voltem no tempo para rastrear a origem de um problema, identificar onde ele ocorreu e em que condições.
-   Detecção de padrões anômalos: Logs consistentes podem revelar padrões incomuns de comportamento, como aumento de erros ou falhas em momentos específicos. Isso pode indicar a presença de falhas em determinados processos ou a necessidade de ajustes no sistema.
-   Resolução de incidentes: Em caso de falha ou problema, os logs são uma fonte de informações crucial para identificar a causa do incidente. Através deles, os engenheiros podem entender os detalhes do erro e implementar soluções mais eficazes e rápidas.
-   Auditoria e conformidade: Logs também podem ser usados para auditorias, garantindo que o sistema esteja funcionando de acordo com padrões de conformidade e segurança. Eles permitem o rastreamento de quem acessou o sistema, que ações foram realizadas e quando.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/kmyq8tggzjcgs2f5adrj.jpg)

Assim como os logs em sistemas de software, o Sensor Libre 2 mantém um registro contínuo dos níveis de glicemia do usuário. Esses registros históricos são fundamentais para o diagnóstico de problemas e para o ajuste do tratamento do diabetes.

-   Rastreabilidade dos níveis de glicose: Os registros do Sensor Libre 2 permitem que o usuário e os profissionais de saúde revisem as variações glicêmicas ao longo do tempo, da mesma forma que os logs rastreiam eventos em um sistema. Se o paciente teve uma hiperglicemia ou hipoglicemia, é possível voltar e analisar o histórico para identificar o que pode ter causado essa variação, como alimentação ou medicação.
-   Detecção de padrões anômalos: Assim como os logs ajudam a identificar padrões anômalos no desempenho de um sistema, os registros de glicemia do Sensor Libre 2 revelam padrões de flutuação nos níveis de açúcar no sangue. Isso pode ser útil para identificar tendências, como quedas de glicose durante a noite ou picos após refeições, que indicam necessidade de ajustes na insulina ou na dieta.
-   Resolução de problemas de saúde: Os registros contínuos do sensor permitem que os médicos tomem decisões baseadas em dados históricos, entendendo como o corpo do paciente reage a diferentes fatores ao longo do tempo. Assim como os logs auxiliam engenheiros a resolver falhas no sistema, os dados do sensor ajudam a ajustar o tratamento de forma personalizada, prevenindo crises de hipoglicemia ou hiperglicemia.
-   Auditoria de saúde: De forma similar à auditoria de logs em sistemas de TI, os registros do Sensor Libre 2 servem como uma auditoria da saúde do paciente, mostrando todos os eventos e mudanças nos níveis de glicose. Esses dados são importantes tanto para avaliações clínicas quanto para garantir que o paciente está seguindo o plano de tratamento de maneira eficaz.
    

### 5. Alertas: Ação Proativa

Os alertas são notificações automáticas acionadas quando determinadas métricas ou eventos atingem condições pré-definidas, indicando que há algo fora do esperado no sistema. Esses alertas são fundamentais para garantir que os administradores ou operadores de sistemas sejam informados rapidamente sobre potenciais problemas, possibilitando ações preventivas ou corretivas antes que os erros se agravem.

Em um sistema observável, as métricas, logs e traces (rastreamentos) são monitorados continuamente para garantir que o sistema esteja funcionando corretamente. Quando certos parâmetros ultrapassam limites predefinidos, um alerta é disparado, notificando a equipe responsável. Esses limites, também conhecidos como limiares ou thresholds, podem ser configurados com base em vários critérios, como o uso de CPU, latência de rede, taxa de erro em uma API, ou outros indicadores de desempenho ou saúde do sistema.

O Sensor Libre 2 possui um sistema de alertas projetado para ajudar os usuários a monitorar e gerenciar seus níveis de glicose de forma eficaz. Os alertas são um recurso crucial que notifica os usuários quando os níveis de glicose estão fora da faixa ideal, permitindo intervenções rápidas para prevenir complicações, como hipoglicemia ou hiperglicemia.

Quando os níveis de glicose do usuário se movem além dos limites definidos (acima do limite superior ou abaixo do limite inferior), o sensor detecta essa alteração imediatamente. Essa detecção é essencial, pois permite uma resposta rápida a flutuações perigosas nos níveis de glicose.

Assim que um nível de glicose é identificado fora da faixa-alvo, o Sensor Libre 2 envia uma notificação de alerta ao usuário. Os alertas podem ser sonoros, vibratórios ou ambos, dependendo das configurações do dispositivo. Essas notificações são projetadas para serem perceptíveis, mesmo em ambientes barulhentos, garantindo que o usuário tome conhecimento da situação.


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/5dqw6ngwpsphc534g0b6.jpg)


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/89hubf3rwzsivwzkaikg.jpg)


### 6. Conclusão: A Interseção da Tecnologia e da Saúde

A evolução da observabilidade em sistemas tecnológicos está cada vez mais conectada ao mundo da saúde digital, contribuindo para um novo paradigma de monitoramento, tratamento e gestão de condições de saúde. Essa transformação é impulsionada pela integração de sistemas digitais com dispositivos médicos, possibilitando uma abordagem mais proativa, personalizada e eficaz para o cuidado com a saúde. As tecnologias emergentes, que permitem a coleta contínua de dados, análise avançada e automação de respostas, trazem conceitos de observabilidade para o centro da saúde digital.

O Sensor Libre 2 e outros dispositivos de monitoramento contínuo de glicose estão revolucionando o tratamento de condições crônicas, como diabetes, ao proporcionar uma gestão mais eficaz, personalizada e proativa da doença. Esses dispositivos, junto com tecnologias complementares, estão transformando a forma como os pacientes monitoram e controlam seus níveis de glicose, contribuindo para a melhoria da qualidade de vida e a redução de complicações associadas à diabetes.

Os dispositivos modernos de monitoramento não apenas fornecem dados, mas também educam os usuários sobre a gestão da diabetes. Aplicativos conectados muitas vezes incluem recursos educacionais, dicas de gestão e ferramentas para rastreamento de dieta e exercícios. Isso ajuda a empoderar os pacientes, incentivando um papel ativo em seu tratamento e melhorando o engajamento no autocuidado.

Essa abordagem moderna e conectada para o tratamento de diabetes está moldando um futuro mais promissor para aqueles que vivem com condições crônicas.

### 7. Referências

1.  Alerting Techniques for an Observable Platform. Disponível em: [https://coralogix.com/blog/alerting-technique-observable-platform/](https://coralogix.com/blog/alerting-technique-observable-platform/)
    
2.  FreeStyle Libre 2 Plus. Disponível em: [https://www.freestyle.abbott/br-pt/sensor-freestyle-libre-2-plus.html?srsltid=AfmBOop-EzH3sKIQIyrONIR7TOwx_6szX8A1J-B-__24wJ0ehGutgr_I](https://www.freestyle.abbott/br-pt/sensor-freestyle-libre-2-plus.html?srsltid=AfmBOop-EzH3sKIQIyrONIR7TOwx_6szX8A1J-B-__24wJ0ehGutgr_I)
    
3.  Google Site Reliability Engineering Handbook. Monitoring Distributed Systems. O’Reilly Media, 2016.
    
4.  IDF Diabetes Atlas 10th Edition. Disponível em: [https://profissional.diabetes.org.br/wp-content/uploads/2022/02/IDF_Atlas_10th_Edition_2021-.pdf](https://profissional.diabetes.org.br/wp-content/uploads/2022/02/IDF_Atlas_10th_Edition_2021-.pdf)
    
5.  Monitorização contínua da glicose – sistema Flash: tempo no alvo e outras informações. Disponível em: [https://drasuzanavieira.med.br/2017/06/16/monitorizacao-continua-da-glicose-tempo-no-alvo/](https://drasuzanavieira.med.br/2017/06/16/monitorizacao-continua-da-glicose-tempo-no-alvo/)
    
6.  Microsoft Learn. Métricas e KPIs em observabilidade. Disponível em: [https://learn.microsoft.com/metrics-observability](https://learn.microsoft.com/metrics-observability)
    
7.  Sociedade Brasileira de Diabetes. Disponível em: [https://diabetes.org.br/#diabetes](https://diabetes.org.br/#diabetes)
    
8.  The Three Pillars of Observability. Disponível em: [https://sematext.com/glossary/three-pillars-of-observability/](https://sematext.com/glossary/three-pillars-of-observability/)
    
9.  Three Pillars of Observability: Logs vs. Metrics vs. Traces. Disponível em: [https://edgedelta.com/company/blog/three-pillars-of-observability](https://edgedelta.com/company/blog/three-pillars-of-observability)
    
10.  Understanding Metrics, Events, Logs and Traces - Key Pillars of Observability. Disponível em: [https://last9.io/blog/understanding-metrics-events-logs-traces-key-pillars-of-observability/](https://last9.io/blog/understanding-metrics-events-logs-traces-key-pillars-of-observability/)
    
11. What Was Observability Again?. Disponível em: [https://elastisys.com/what-was-observability-again/](https://elastisys.com/what-was-observability-again/)
