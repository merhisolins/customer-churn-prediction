# Predição de Churn no Beta Bank

##  Descrição

O Beta Bank enfrenta desafios na retenção de clientes, pois muitos estão cancelando suas contas mensalmente. Como manter clientes existentes é mais econômico do que adquirir novos, este projeto tem como objetivo construir um modelo de **Machine Learning** capaz de prever quais clientes têm maior probabilidade de sair do banco.

O modelo será avaliado com base na métrica **F1-score**, com um valor mínimo de **0,59** para aprovação. Além disso, a métrica **AUC-ROC** será calculada para comparação com o F1-score e melhor interpretação do desempenho do modelo.

---

## Conjunto de Dados

Atualmente, o conjunto de dados utilizado neste projeto inclui as seguintes colunas:

- **Customer ID** – Identificador único do cliente  
- **Credit Score** – Pontuação de crédito  
- **Age** – Idade do cliente  
- **Balance** – Saldo da conta bancária  
- **Estimated Salary** – Salário estimado do cliente  
- **Tenure** – Tempo de relacionamento com o banco (em anos)  
- **Num of Products** – Número de produtos contratados no banco  
- **Has Credit Card** – O cliente possui um cartão de crédito? (0 = Não, 1 = Sim)  
- **Is Active Member** – O cliente é um membro ativo do banco? (0 = Não, 1 = Sim)  
- **Exited** – Cliente cancelou a conta? (0 = Não, 1 = Sim) *(Variável alvo – Churn)*  

---

## Arquitetura e Tecnologias Utilizadas

Este projeto segue princípios de **arquitetura modular**, garantindo escalabilidade e reutilização de código. A estrutura é organizada em camadas:

🔹 **Camada de Dados**: Processamento e tratamento dos dados utilizando **Pandas** e **NumPy**.  
🔹 **Camada de Análise**: Estatística descritiva, análise exploratória e balanceamento de classes.  
🔹 **Camada de Modelagem**: Implementação e avaliação de modelos de aprendizado de máquina.  
🔹 **Camada de Apresentação**: Visualização de insights através de gráficos e relatórios interativos.  

### **Principais Tecnologias e Bibliotecas**  

 **Python 3.8+** – Linguagem base para análise e processamento de dados.  
 **Pandas / NumPy** – Manipulação e tratamento de dados estruturados.  
 **Matplotlib / Seaborn** – Visualização de dados e gráficos avançados.  
 **Scikit-Learn** – Modelos de aprendizado de máquina e métricas de avaliação.  
 **Jupyter Notebook** – Desenvolvimento interativo e documentação dos insights.  

---
