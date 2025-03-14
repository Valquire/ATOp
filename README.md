# Autonomia de Meios Operativos - ATOp

## License
This project use Creative Commons Legal Code (CC0 1.0 Universal)

## Abstract
In complex military scenarios, logistical planning requires a high degree of precision, especially regarding the autonomy of operational elements --- defined as the ability to remain active without external resupply. This autonomy is influenced by multiple factors, such as supply consumption, crew size, and conditions of deployment. Although Machine Learning (ML) techniques are employed to predict logistical demands, the semantic heterogeneity of the data and the lack of contextual domain knowledge limit the effectiveness of purely quantitative approaches. Aiming to overcome these challenges, this study proposes the ATOp (Autonomia de Meios Operativos, in portuguese) approach, which semantically enriches domain data by combining Ontology-Driven Conceptual Modeling (ODCM) with ML to improve predictive accuracy. ATOp is underpinned by the Unified Foundational Ontology (UFO) and the OntoUML language to structure naval domain knowledge, making explicit various situations (e.g., underway or moored) and consumption variables (fuel, food, lubricants). This ontological perspective enables a semantic segmentation of the data, powering a regression pipeline based on an ensemble method, which coordinates multiple specialized models. The research included designing a specific ontology, collecting and integrating structured data from the \emph{Sistema de Informações Gerenciais do Abastecimento} (SINGRA) and unstructured data from the Relatórios de Fim de Comissão (RFC) of the Brazilian Navy, as well as carrying out experiments evaluated by performance metrics such as R^2 and RMSE. The findings reveal that combining ontologies with ML techniques reduces noise and improves predictive accuracy, outperforming conventional methods. As a contribution, ATOp demonstrates the importance of a robust semantic layer in decision-making contexts, providing a replicable, high-performance model for critical domains such as Command and Control (C²) systems.

## Authors
- **Valquire da Silva de Jesus** - [@Valquire](https://github.com/Valquire)
- **Kelli de Faria Cordeiro**
- **Giseli Rabello Lopes**
