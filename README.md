# Atividade-em-grupo---15-10-2024
# Gestão de Perdas na Colheita de Cana-de-açúcar

## Descrição do Problema

A colheita de cana-de-açúcar é uma etapa crítica na produção de açúcar e etanol, e as perdas durante esse processo podem ter um impacto significativo na rentabilidade do setor.  As perdas podem ocorrer por diversos fatores, como falhas na colheitadeira, condições climáticas adversas, tipo de terreno e variedades de cana. 

Este projeto visa solucionar o problema do gerenciamento de perdas na colheita de cana-de-açúcar, fornecendo um sistema que permite o registro detalhado das perdas, incluindo a localização, a quantidade e o tipo de perda. O sistema também gera relatórios em formato JSON para facilitar a análise e a tomada de decisão.

##Problemas do Agronegócio Abordados pelo Código:

Perdas Quantitativas: A cana-de-açúcar pode ser perdida no campo por diversos motivos, como falhas na colheitadeira, condições climáticas adversas, ou dificuldades no terreno. O código permite registrar a quantidade de cana perdida, auxiliando na quantificação do problema e na identificação de padrões.
Perdas Qualitativas: A qualidade da cana-de-açúcar colhida também é afetada por perdas. A cana deixada no campo pode deteriorar, impactando a qualidade do açúcar e do etanol produzidos. O sistema permite registrar o tipo de perda, como "cana deixada no campo", "cana amassada" ou "cana queimada", o que auxilia na análise da qualidade da cana colhida.
Localização das Perdas: A geolocalização das perdas é um fator importante para a análise espacial do problema. O código registra a localização das perdas, permitindo a identificação de áreas com maior índice de perdas e a investigação das causas. Essa informação é crucial para otimizar as operações de colheita e direcionar investimentos em maquinário ou treinamento.
Rastreabilidade: O código registra o ID do talhão onde a perda ocorreu, permitindo a rastreabilidade das perdas e a análise do histórico de cada talhão. Essa informação é valiosa para a tomada de decisão em relação ao manejo do solo, escolha de variedades e práticas de colheita.

##Descrição Detalhada do Código Python para Gestão de Perdas na Colheita de Cana-de-açúcar

Este código Python se propõe a solucionar um problema crucial no agronegócio brasileiro: o gerenciamento de perdas na colheita de cana-de-açúcar.  A perda de cana durante a colheita impacta diretamente a produtividade e a rentabilidade do setor, tornando a gestão eficiente dessas perdas uma necessidade. O código utiliza conceitos de subalgoritmos, estruturas de dados, manipulação de arquivos e conexão com banco de dados para construir um sistema robusto de registro e análise de perdas.

## Funcionalidades

Conexão com o Banco de Dados Oracle:
A função conectar_banco() estabelece a conexão com o banco de dados, garantindo a persistência e a organização dos dados. O uso de um banco de dados como o Oracle oferece escalabilidade e segurança para o sistema.
Cadastro de Talhões:
A função cadastrar_talhao() permite o cadastro detalhado de cada talhão, incluindo informações importantes como a variedade da cana-de-açúcar, a idade do canavial, a área do talhão e a geolocalização. Esses dados são essenciais para a análise das perdas e para a tomada de decisão no manejo da cultura.
Registro de Perdas:
A função registrar_perda() registra as perdas de forma detalhada, incluindo o tipo de perda, a quantidade, a localização e o talhão afetado. Essa função é fundamental para a coleta de dados e para o monitoramento das perdas ao longo do tempo.
Exemplo de Uso:

O código inclui um exemplo prático de como utilizar as funções para cadastrar um talhão e registrar uma perda. Isso facilita a compreensão do funcionamento do sistema e a sua aplicação em cenários reais.

##Relação com os Conteúdos Estudados:

Subalgoritmos: As funções conectar_banco(), cadastrar_talhao() e registrar_perda() demonstram o uso de subalgoritmos para modularizar o código e facilitar a sua reutilização e manutenção.
Estruturas de Dados: O código utiliza tuplas para armazenar os dados de forma organizada antes de inseri-los no banco de dados.
Manipulação de Arquivos: O código pode ser adaptado para receber dados de arquivos JSON, o que possibilita a integração com sistemas de sensores e outras tecnologias de coleta de dados.
Conexão com Banco de Dados: O uso do módulo cx_Oracle para conectar ao banco de dados Oracle demonstra a capacidade de integrar o sistema com uma solução robusta e escalável para armazenamento de dados.


## Tecnologias Utilizadas

* **Python:** Linguagem de programação utilizada para desenvolver o sistema.
* **cx_Oracle:** Módulo Python para conectar e interagir com o banco de dados Oracle.
* **JSON:** Formato de arquivo utilizado para gerar os relatórios de perdas.

##Conclusão:

Este código Python representa uma solução promissora para o problema de gestão de perdas na colheita de cana-de-açúcar. Ele aborda problemas reais do agronegócio, utiliza conceitos importantes da programação e pode ser expandido para criar um sistema completo de gestão agrícola. A sua capacidade de integração com outras tecnologias e a possibilidade de gerar insights valiosos para a tomada de decisão o tornam uma ferramenta poderosa para aumentar a eficiência e a rentabilidade no setor sucroalcooleiro.
