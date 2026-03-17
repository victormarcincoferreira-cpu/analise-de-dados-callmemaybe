# 📊 Análise de Dados — Plataforma CallMeMaybe

## 📌 Sobre o projeto
Este projeto consiste em uma análise exploratória de dados operacionais de chamadas da plataforma **CallMeMaybe**, com o objetivo de identificar padrões de uso e fatores que impactam o desempenho das operações de atendimento telefônico.

A análise foi desenvolvida como projeto final da plataforma TripleTen, unindo tratamento de dados, exploração analítica e visualização de resultados.

---

## 🎯 Objetivo
Investigar o comportamento das chamadas e gerar insights que auxiliem na tomada de decisão, especialmente em relação a:

- eficiência operacional  
- volume de chamadas  
- chamadas perdidas  
- impacto do tempo de espera  

---

## 🏢 Contexto do negócio
A CallMeMaybe é uma plataforma de telefonia virtual utilizada por empresas que gerenciam grandes volumes de chamadas.

Essas empresas utilizam o sistema para:
- realizar chamadas externas com clientes  
- receber chamadas de entrada  
- realizar chamadas internas entre operadores  

---

## ❓ Perguntas de análise
Durante o projeto, foram investigadas questões como:

- Existe relação entre tempo de espera e chamadas perdidas?  
- Há diferença de comportamento entre planos tarifários?  
- Qual a proporção de chamadas perdidas?  
- A duração das chamadas varia conforme o tipo?  

---

## 🛠️ Tecnologias utilizadas
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Tableau  

---

## 📊 Análise realizada
- Limpeza e tratamento de dados  
- Análise exploratória (EDA)  
- Criação de métricas relevantes  
- Visualização de dados  
- Construção de dashboard interativo  

---

## 📈 Principais insights

- A taxa de chamadas perdidas é elevada (46,6%), representando um ponto crítico na operação  
- Chamadas realizadas por operadores apresentam maior probabilidade de não serem completadas, sugerindo influência do comportamento de resposta dos clientes  
- Foram identificadas diferenças de comportamento entre clientes de diferentes planos tarifários  
- Operadores mais ativos tendem a apresentar melhor desempenho, com menor proporção de chamadas perdidas  

---

## 💡 Possíveis recomendações

- Reduzir o tempo de espera para diminuir chamadas perdidas  
- Avaliar estratégias de contato com clientes para aumentar taxa de resposta  
- Investigar práticas dos operadores mais eficientes

  ---

## 📊 Dashboard
Acesse o dashboard interativo:

👉 https://public.tableau.com/app/profile/victor.ferreira1121/viz/Projeto_Final_17737080949930/Painel1?publish=yes

---

## 🎤 Apresentação
Veja a apresentação do projeto:

👉 https://drive.google.com/file/d/1w0NGyC1fjlzW-ivnYBGRrCgmp070Xl1V/view

---

## 📁 Dados utilizados

### 📞 Chamadas — `telecom_dataset_new.csv`
Contém registros de chamadas realizadas na plataforma.

Principais variáveis:
- user_id  
- date  
- direction  
- operator_id  
- is_missed_call  
- call_duration  
- total_call_duration  

---

### 👥 Clientes — `telecom_clients.csv`
Contém informações sobre os clientes.

Principais variáveis:
- user_id  
- tariff_plan  
- date_start  

---

## 🚀 Como executar o projeto

1. Clone o repositório:
```bash
git clone https://github.com/victormarcincoferreira-cpu/analise-de-dados.git
