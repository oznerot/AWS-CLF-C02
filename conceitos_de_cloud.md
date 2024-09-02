# Conceitos de Cloud
## O que é Cloud Computing
Cloud computing é a prática de usar uma rede de servidores remotos hosteados na Internet para armazenar, gerenciar e processar dados, ao invés de usar servidores locais ou um computador pessoal.

Em um modelo de negócios em Cloud, temos dois atores:  
O Usuário:
- Solicita o servidor;
- Contrata os TI;
- Paga ou aluga o imobiliário;
- Assume os ricos;

O Procedor Cloud:
- Configura os servidores Cloud

## Evolução da Hospedagem em Cloud
Antigamente, se você quisesse hospedar um site web, você precisaria de um servidor dedicado. Isso não era muito prático pelos seguintes motivos:
- Uma única máquina era dedicada a um único negócio, ou seja um único servidor rodava apenas um único web site;
- Por causa disso, era muito custoso e necessitava de manuntenção constante, apesar de possuir uma alta segurança.

Em razão disso, surgiram então, os Virtual Private Server (VPS). Consistia na utilização de técnicas de virtualização para rodar vários serviços em uma mesma máquina, sem que eles competissem pelos recursos devido à isolação. Porém, ainda era necessária a utilização de uma máquina física e ainda servia a um único negócio.

Depois disso, surgiu a Hospedagem Compartilhada. Nesse modelo de hospedagem, uma única máquina era compartilhada por vários negócios. Porém caso um dos locatários decidisse utilizar um pouco mais do poder de processamento, isso prejudicaria o desempenho dos outros negócios devido ao péssimo isolamento e funcionalidades limitadas.

Por fim, surgiu a Hospedagem em Núvem. Nesse modelo, múltiplas máquinas atuam como um único sistema. Esse sistema é abstraído em múltiplos serviços em nuvem. Esse modelo juntou todas as vantagens dos modelos anteriores:
- Flexibilidade;
- Escalabilidade;
- Segurança;
- Custo-benefício;
- Alta configurabilidade.

## O que é a Amazon?
Fundada por Jeff Bezos em 1994, a compania começou como uma loja online de livros que expandiu para outros produtos.
Porém, hoje em dia ela é muito mais que isso e expandiu para as áreas de:
- Computação em Núvem;
- Streaming Digital (Prime Video, Prime - Music, Twitch);
- Mercados (Whole Food Market);
- Inteligência Artificial;
- Satélites de Baixa Orbita (Kuniper Systems);
- e muito mais.

## O que é a AWS?
É o nome do serviço de provedor de nuvem da Amazon.

O primeiro serviço de cloud oferecido foi o **Simple Queue Service (SQS)** em 2004.
<br></br>
Em Março de 2006, a AWS lançou o **Simple Storage Service (S3)**.
<br></br>
Em Agosto de 2006, a AWS lançou o **Elastic Compute Cloud (EC2)**.
<br></br>
Em Novembro de 2010, todos os sites de varejo da Amazon.com foram migrados para AWS

## O que é um Cloud Service Provider (CSP)?
Um CSP é um compania que:
- provê múltiplos Cloud Services;
- os Cloud Services podem ser ligadas para criar arquiteturas Cloud;
- os Cloud Services são acessados por uma única API conjunta. Por exemplo, AWS API;
- os Cloud Services utilizam uma cobrança medida baseada na utilização. Por exemplo, por segundo, por hora;
- os Cloud Services possuem uma ferramenta de monitoramento built-in. Por exemplo