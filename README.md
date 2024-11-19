


# Global Solutions
<p align="center">  <img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>  </p>

Repositório criado para a organização e hospedagem dos projetos da Global Solutions da FIAP, correspondente ao 3º semestre do curso de Análise e Desenvolvimento de Sistemas.

## Índice
 * [Global Solutions](#challenge-odontoprev)
 * [Índice](#índice)
 * [Video Pitch](#%EF%B8%8F-Video-Pitch)
 * [Desafios e Problemas](#%EF%B8%8F-desafios-e-problemas)
 * [Solução Apresentada](#-solução-apresentada)
 * [Disciplinas](#%EF%B8%8F-disciplinas)
 * [Tecnologias Utilizadas](#%EF%B8%8F-tecnologias-utilizadas)
 * [Equipe](#-equipe)

## 📹 Video Pitch

Em construção

[:arrow_up: voltar para o índice :arrow_up:](#índice)

## ⁉️ Desafios e Problemas

**Desafio**

Criar um mapa interativo utilizando fotos enviadas pelos clientes que serão mapeadas com IA para identificar os equipamentos elétricos de um apartamento,  de dois quartos, sala, cozinha, banheiro e lavanderia, que mostre o consumo de energia em tempo real utilizando cores que variam do verde claro ao vermelho, indicando os pontos de maior consumo.

**Problema**

Em um cenário global cada vez mais afetado pelas mudanças climáticas e pela crescente necessidade de fontes de energia limpas e renováveis, a transição para um modelo energético sustentável tornou-se uma prioridade. Governos, empresas e a sociedade civil estão unindo esforços para desenvolver soluções que promovam equilíbrio ambiental e econômico. Nesse contexto, a inovação tecnológica surge como uma aliada indispensável, possibilitando avanços em geração, armazenamento e consumo de energia.

Nossa solução automatiza sua residência, proporcionando eficiência, segurança e economia. Com o nosso sistema, você identifica os principais pontos de manutenção e consumo, reduz gastos com energia e contribui para a preservação do meio ambiente ao aderir as nossas sugestões de equipamentos sustentáveis e que consomem uma quantidade menor de energia. Além disso, cuidamos do seu conforto financeiro, notificando sobre reparos necessários ou alterações nos custos. Assim, você mantém o controle total da sua conta de luz e planeja futuros reparos com tranquilidade, sem surpresas desagradáveis.

## ⁉️ Contexto

O projeto tem como foco desenvolver uma solução inovadora e sustentável para o monitoramento e controle de consumo de energia elétrica em residências, com o objetivo de promover a conscientização sobre o uso eficiente de energia, reduzir custos e minimizar o impacto ambiental. A iniciativa combina tecnologias avançadas através de um painel que será conectado ao quadro de energia, como inteligência artificial e sistemas automatizados, para oferecer aos moradores maior controle sobre seu consumo de energia, além de incentivos para a adoção de práticas mais sustentáveis. Por meio de um sistema inteligente e interativo, o projeto visa transformar o relacionamento das pessoas com a energia que consomem em suas casas, alinhando eficiência, segurança e economia.

Utilizando ferramentas modernas como .NET para desenvolvimento de software e Python para análise de dados, o sistema integra sensores para monitoramento em tempo real, um mapa interativo para visualização de consumo por ambiente e um dashboard com gráficos e estimativas financeiras. Com base na análise de padrões de consumo, o sistema fornecerá alertas sobre áreas de desperdício, sugestões de economia e recomendações de manutenção preventiva, além de indicar a aquisição de novos equipamento s que consomem uma quantidade menor de energia, além de evitar o uso excessivo com energia limpa, ajudando os moradores a reduzir sua pegada ecológica e custos operacionais. Essa abordagem tecnológica busca unir praticidade e inovação ao cuidado com o meio ambiente, oferecendo uma solução completa para residências inteligentes.

## Nossa essência

**Servir, cuidar e economizar.** 

Automatizamos sua residência para garantir eficiência, segurança e economia. Com nosso sistema, você identifica os pontos críticos de manutenção e consumo, economiza energia e cuida do meio ambiente. Tudo isso enquanto cuidamos da sua casa e da sua tranquilidade financeira, avisando você sobre qualquer necessidade de reparo ou mudança nos custos. Assim, você sabe exatamente onde está economizando e mantém o controle da sua conta de luz e dos reparos futuros, sem preocupações.

[:arrow_up: voltar para o índice :arrow_up:](#índice)

## 🚩 Solução Apresentada

# Objetivo Geral

Desenvolver um sistema inteligente de monitoramento e controle de consumo de energia elétrica em residências, utilizando .NET e inteligência artificial com Python, para promover a conscientização sobre o uso eficiente de energia e a redução de custos.

# Objetivos Específicos

## Mapeamento do Consumo de Energia

Criar um mapa interativo utilizando fotos enviadas pelos clientes que serão mapeadas com IA para identificar os equipamentos elétricos de um apartamento,  de dois quartos, sala, cozinha, banheiro e lavanderia, que mostre o consumo de energia em tempo real utilizando cores que variam do verde claro ao vermelho, indicando os pontos de maior consumo.

## Monitoramento em tempo real

Implementar um sensor de energia junto ao painel de energia principal da casa , que vai mapear vários pontos do apartamento para coletar dados de consumo em tempo real e enviar essas informações para o servidor.

## Análise de dados e previsão de consumo

Utilizar técnicas de machine learning para analisar os dados coletados, prever o consumo de energia e identificar padrões de uso que possam indicar desperdícios ou necessidade de manutenção. 

## Visualização e feedback ao usuário

Desenvolver um dashboard e uma mapa interativo que permita aos moradores visualizar o consumo de energia em tempo real, com gráficos e alertas sobre áreas de alto consumo e sugestões de economia. Além de enviar feedbacks com frequência para avaliar nossos treinamentos, sugestões, indicações de valores e serviçocs prestados.

## Estimativa de custos

Calcular e exibir a estimativa do valor da conta de luz com base no consumo atual, ajudando os moradores a entenderem o impacto financeiro do uso de energia. Essa estimativa foi criado com o treinamento da IA, com base nos dados coletados pelo portal da ENEL, que mostra os valores em tabelas e regras de negócio.

## Recomendações de manutenção

Fornecer recomendações específicas sobre onde realizar manutenção ou ajustes para reduzir o consumo de energia, baseadas na análise dos dados coletados. O cliente pode até trocar o item de acordo com as sugestões de produtos e serviços que vamos recomendar em parceiria com nossos prestadores.

## Integração de tecnologias

Integrar as tecnologias .NET para o desenvolvimento do frontend e backend, e Python para a coleta e análise de dados, garantindo uma comunicação eficiente entre os componentes do sistema. O banco de dados vai receber informações de várias tecnologias para que possamos consumir nas aplicações Mobile e Web Interface.

# Estrutura do projeto

# Mapeamento do Apartamento

## Frontend

Usar uma biblioteca de visualização como o Blazor no .NET para criar a interface do usuário. Desenhar o mapa do apartamento e usar cores para indicar o consumo de energia, quando clicar ou passar o mouse em cada ambiente, mostrar uma caixa contendo detalhes dos itens que constam em cada ambiente, qual o nível de consumo e possível custo que pode impactar em na conta no final do mês.

## Backend

Utilizar ASP.NET Core para gerenciar a lógica do servidor e a comunicação com o banco de dados.

# Monitoramento de Energia

## Sensores

Instalar sensores de consumo de energia em diferentes pontos do apartamento. Esses sensores podem enviar dados em tempo real para o servidor.

## Coleta de Dados

Use Python para coletar e processar os dados dos sensores. Bibliotecas como pandas e NumPy podem ser úteis para análise de dados.

## Análise de Dados e IA

Machine Learning: 

Utilizar ML.NET para criar modelos de machine learning que possam prever o consumo de energia e identificar padrões. Será realizado o treinamento com modelos para detectar anomalias e sugerir manutenção.

## Visualização e Conscientização

**Dashboard**

Criar um dashboard interativo que mostre o consumo de energia em tempo real. Usar gráficos e cores para indicar áreas de alto consumo.

**Alertas e Recomendações**

Baseado nos dados analisados, enviar alertas para os moradores sobre áreas que precisam de manutenção ou onde podem economizar energia.

## Tecnologias e Ferramentas

**.NET** Para o desenvolvimento do frontend e backend.
**Blazor** Para a criação de interfaces interativas.
**ML.NET** Para machine learning e análise de dados.
**Python** Para coleta e processamento de dados, e tarefas avançadas de IA.
**Sensores de Energia** Para monitoramento em tempo real.
**Azure** Para hospedagem e serviços de IA, como o Azure Machine Learning.

[:arrow_up: voltar para o índice :arrow_up:](#índice)

## 🗂️ Disciplinas
* [DevOps Tools & Cloud Computing](https://github.com/patinaomi/global-solutions-fiap-3-sem/tree/main/DevOps_Tools_And_Cloud_Computing)
* [Compliance, Quality Assurance & Tests](https://github.com/patinaomi/global-solutions-fiap-3-sem/tree/main/Compliance_Quality_Assurance_And_Tests)
* [Mastering Relational and Non-Relational Database](https://github.com/patinaomi/global-solutions-fiap-3-sem/tree/main/Mastering_Relational_And_Non_Relational_Database)
* [Advanced Business Development with .Net](https://github.com/patinaomi/global-solutions-fiap-3-sem/tree/main/Advanced_Business_With_Dot_Net)
* [Disruptive Architectures: IOT, IOB & Generative IA](https://github.com/patinaomi/global-solutions-fiap-3-sem/tree/main/Disruptive_Architectures_IOT_And_IOB)
* [Java Advanced](https://github.com/patinaomi/global-solutions-fiap-3-sem/tree/main/Java_Advanced)
* [Mobile Application Development](https://github.com/patinaomi/global-solutions-fiap-3-sem/tree/main/Mobile_Application_Development)

[:arrow_up: voltar para o índice :arrow_up:](#índice)

## 🛠️ Tecnologias Utilizadas
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white) <br>
![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) 

[:arrow_up: voltar para o índice :arrow_up:](#índice)

## 🧑‍🤝‍🧑 Equipe

| <h3>Claudio Bispo</h3><img src="https://avatars.githubusercontent.com/u/110735259?v=4" width=180px> <h6>RM553472</h6> <a href="https://github.com/Claudio-Silva-Bispo"><img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"></a> <a href="https://www.linkedin.com/in/claudiosbispo"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"></a> <a href="https://www.instagram.com/_claudiobispo/"><img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white"></a>|<h3>Patricia Naomi</h3> <img src="https://avatars.githubusercontent.com/u/132932532?v=4" width=180px><h6>RM552981</h6> <a href="https://github.com/patinaomi"><img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"></a> <a href="https://www.linkedin.com/in/patinaomi/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"></a> <a href="https://www.instagram.com/naomipati/"><img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white"></a>|
|--|--|


[:arrow_up: voltar para o índice :arrow_up:](#índice)
