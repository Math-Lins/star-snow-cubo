# Atividade 1 - Star Schema
Arquivo com a tabela e as competências solicitadas na atividade.

#Atividade 2 - Tabelas 
Arquivos das três solicitações:
1- com as tabelas solicitadas
2- as funções para execução
3- com as queries para concluir a atividade 2

# Pesquisa de Star-Snow-Cubo 

Star Schema

Casos de Uso: 

Análise de Vendas e Marketing: Utilizado para acompanhar as vendas por produto, região, período de tempo, etc. 

Exemplo: análise de performance de vendas por região e por canal de vendas. 

Finanças e Contabilidade: Ideal para relatórios financeiros, como análise de despesas, receitas e lucros por centro de custo, período fiscal, etc. 

Operações de Loja: Utilizado para monitorar o desempenho de lojas, incluindo inventário, transações de ponto de venda, e análise de clientes. 

Telecomunicações: Para análise de chamadas, uso de dados, e performance de redes em diferentes regiões e períodos. 

Healthcare: Para monitorar pacientes, tratamentos, e resultados médicos em hospitais ou clínicas.


Snowflake


Casos de Uso:

Sistemas de Data Warehouse Grandes e Complexos: Adequado para grandes organizações onde a normalização ajuda a manter a integridade dos dados e reduzir a redundância. 

Análises Detalhadas e Multi-Dimensionais: Quando há necessidade de análises detalhadas que requerem múltiplas dimensões e subdimensões (por exemplo, detalhes demográficos complexos de clientes). 

Ambientes com Estruturas de Dados Muito Complexas: Quando as relações entre dimensões são complexas e a manutenção de dados precisa ser meticulosa. 

Empresas que Valorizam a Economia de Armazenamento: Quando o espaço de armazenamento é uma preocupação significativa e a redução da redundância é crítica. 

Educação: Para análise detalhada de dados de estudantes, cursos, departamentos e desempenho acadêmico.


Cubos OLAP

Definição de Cubo OLAP:

OLAP (Online Analytical Processing) refere-se a uma categoria de sistemas de software que são usados para análise multidimensional de grandes volumes de dados. Um cubo OLAP é uma estrutura de dados que permite a realização de consultas complexas e rápidas em um banco de dados. Ele organiza os dados em um formato multidimensional, permitindo a exploração e análise de dados de várias perspectivas. Cada dimensão do cubo representa uma característica diferente dos dados, como tempo, localização, produtos, etc.


Arquitetura de Cubo OLAP 

A arquitetura de um cubo OLAP geralmente inclui: 

Fonte de Dados: Pode incluir diversos tipos de fontes de dados, como bancos de dados relacionais, arquivos CSV, e sistemas ERP. 

Processo de ETL (Extract, Transform, Load): Extrai dados das fontes, transforma-os para o formato desejado e carrega-os no armazém de dados. 

Armazém de Dados (Data Warehouse): Armazena os dados já processados, preparados para análise OLAP. 

Servidores OLAP: Manipulam o cubo OLAP e respondem às consultas de usuários.
  
 Podem ser de diferentes tipos: 

* MOLAP (Multidimensional OLAP): Os dados são armazenados em uma estrutura multidimensional especializada. 

* ROLAP (Relational OLAP): Os dados são armazenados em tabelas relacionais tradicionais, mas a funcionalidade OLAP é implementada no nível da consulta. 

* HOLAP (Hybrid OLAP): Combina características de MOLAP e ROLAP.

* Ferramentas de Cliente OLAP: São interfaces de usuário, como dashboards e relatórios, que permitem aos usuários finais interagir com os dados do cubo OLAP.



Implementação de Cubo OLAP 

A implementação de um cubo OLAP envolve várias etapas: 

1- Definição de Requisitos: Identificação das necessidades de negócio, métricas a serem analisadas e dimensões necessárias. 

2- Modelagem de Dados: Criação do modelo multidimensional que define as dimensões e medidas do cubo. 

3- ETL: Desenvolvimento do processo de ETL para extrair dados das fontes, transformá-los e carregá-los no armazém de dados. 

4- Construção do Cubo: Configuração do cubo OLAP no servidor OLAP escolhido, definindo dimensões, hierarquias, medidas e cálculos. 

5- Otimização: Ajuste de desempenho do cubo OLAP, otimizando consultas e melhorando a eficiência de armazenamento. 

6- Testes: Realização de testes de funcionalidade, desempenho e segurança. 

7- Implantação: Disponibilização do cubo OLAP para os usuários finais. 

8- Manutenção: Monitoramento contínuo e atualização do cubo OLAP conforme necessário.

