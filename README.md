# das-2-2025-2

# Aula 30/07

amazon SQS / amazon EC2 / amazon S3

- Well Architect Framework

É um modelo criado pela Amazon (AWS) com o objetivo de orientar arquitetos e desenvolvedores na construção de ambientes em nuvem que sejam seguros, eficientes, resilientes e otimizados em custo. Ele serve como um guia de boas práticas para avaliar e melhorar arquiteturas na nuvem, com base em princípios que garantem a qualidade e a sustentabilidade dos sistemas ao longo do tempo.

O framework é estruturado em seis pilares: excelência operacional, segurança, confiabilidade, eficiência de performance, otimização de custos e sustentabilidade. A excelência operacional trata da capacidade de executar e monitorar sistemas para entregar valor de forma contínua, promovendo a melhoria constante. O pilar de segurança aborda a proteção de dados e sistemas, incluindo o controle de acesso, criptografia e a resposta a incidentes. A confiabilidade diz respeito à capacidade de um sistema de se recuperar de falhas e continuar funcionando conforme esperado, o que envolve práticas como backup, tolerância a falhas e escalabilidade.

Já a eficiência de performance foca em usar recursos computacionais de maneira eficaz, ajustando a infraestrutura conforme a demanda e escolhendo as tecnologias adequadas para cada caso. O pilar de otimização de custos busca eliminar desperdícios e garantir que os recursos sejam utilizados com o melhor custo-benefício possível. Por fim, a sustentabilidade, adicionada mais recentemente ao framework, considera o impacto ambiental das workloads, incentivando decisões que reduzam o consumo de energia e melhorem a eficiência ecológica.

Ao aplicar o este modelo, as equipes podem identificar riscos e oportunidades de melhoria em suas arquiteturas, utilizando inclusive a ferramenta Well-Architected Tool, oferecida pela própria AWS, para realizar revisões sistemáticas. Em resumo, o framework ajuda organizações a criar soluções robustas e preparadas para o crescimento sustentável na nuvem.
  
- Trade-off

Em resumo, é uma prática de tomar decisões equilibradas, ponderando os impactos de cada escolha sobre os diferentes pilares da arquitetura. Trata-se de buscar a melhor combinação possível entre segurança, performance, custo, confiabilidade, sustentabilidade e operação, levando sempre em conta o contexto específico do sistema e do negócio. Esse processo é fundamental para construir soluções eficientes, resilientes e alinhadas com os objetivos estratégicos na nuvem.

O conceito de trade-off, dentro do AWS Well-Architected Framework, é central para o processo de tomada de decisões em arquitetura de sistemas na nuvem. Ele se refere à necessidade de equilibrar diferentes prioridades e restrições ao projetar e operar workloads, levando em conta os objetivos de negócio, os recursos disponíveis e os riscos aceitáveis. Em outras palavras, trade-offs são compromissos conscientes entre vantagens e desvantagens de diferentes opções técnicas.

Ao aplicar o framework, os arquitetos são incentivados a analisar cada decisão sob múltiplas perspectivas, muitas vezes representadas pelos próprios pilares do WAF — excelência operacional, segurança, confiabilidade, eficiência de performance, otimização de custos e sustentabilidade. Como esses pilares frequentemente entram em conflito entre si, é preciso escolher cuidadosamente onde investir mais esforço, tempo e recursos, e onde é aceitável abrir mão de certos benefícios para priorizar outros.

EX: para melhorar a confiabilidade de uma aplicação crítica, uma equipe pode optar por replicar dados entre múltiplas regiões, o que melhora a tolerância a falhas e a disponibilidade. No entanto, isso também aumenta os custos de armazenamento e tráfego, além de adicionar complexidade operacional. Nesse caso, há um trade-off claro entre confiabilidade e custo, e cabe à equipe decidir se o ganho em resiliência justifica o investimento adicional.

EX: performance e custo. É possível utilizar instâncias de alta performance com capacidade computacional superior para garantir tempos de resposta rápidos. Entretanto, isso pode ser desnecessário em momentos de baixa demanda, resultando em custos elevados. A alternativa pode ser implementar um sistema de auto scaling que ajuste dinamicamente os recursos conforme o uso. Isso introduz certa complexidade, mas equilibra performance e custo de forma mais eficiente.

# Aula 06/08

- Elastic comput clund

- AWS shared responsibility model
- IaaS / PaaS / Saas - existe mais, mas estes são os 3 basicos.
  
# Aula 13/08

- Cada usuario da AWS pode ter duas chaves para acessar, uma para programar e outra para acessar.
- Cuidar usuario root, é a conta com privilégios máximos em sistemas operacionais.
- Loga com root, habilita NFA. Cria outro usuario de trab, habilita NFA tambem e utiliza para o dia a dia. Para não vazar conta root.
  
- identity basic policy eu associo ela ao usuario dentro do IAM (serviço da AWS)
- resource basic policy
- diferença entre os dois: resource tem que DEFINIR o usuario (principal)

- ATIVADE aws
  - modulo 02, 03

# Aula 20/08

# Aula 27/08

# Aula 10/09

fsx for windows
fsx for NETAPP
fsx for openzfs
fsx forluster HPC
amazon S3 inventory
- gerar um arquivo de texto para usar, encontrar / gerenciar arquivos. Pode demorar até 1 dia para gerar tudo de tantos aquivos.

