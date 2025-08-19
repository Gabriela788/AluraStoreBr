# 🏬 Projeto Alura Store – Análise de Lojas

## 📌 Sobre o Projeto
Este projeto tem como objetivo apoiar o Sr. João, proprietário da rede fictícia **Alura Store**, na decisão de qual loja vender para levantar recursos e investir em um novo empreendimento.  

Foram analisadas **4 lojas** distintas a partir de dados de vendas, avaliações de clientes e informações de frete. O foco foi identificar a loja com **menor eficiência** em termos de faturamento, desempenho por categoria, satisfação dos clientes e competitividade nos custos de frete.  

---

## 🎯 Objetivo
- Identificar a loja menos vantajosa para manter.  
- Recomendar qual loja deve ser vendida.  
- Apoiar a decisão com **análises estatísticas, gráficos e relatórios descritivos**.  

---

## 📂 Estrutura do Projeto
- `loja_1.csv` – Base de vendas da Loja 1  
- `loja_2.csv` – Base de vendas da Loja 2  
- `loja_3.csv` – Base de vendas da Loja 3  
- `loja_4.csv` – Base de vendas da Loja 4  
- `AluraStoreBr.ipynb` – Notebook principal contendo:  
  - Análise exploratória e tratamento de dados  
  - Faturamento total por loja  
  - Vendas por categoria  
  - Média de avaliação dos clientes  
  - Produtos mais e menos vendidos  
  - Frete médio  
  - Gráficos comparativos (barras, rosca, linha por ano)  
  - Relatório conclusivo  

---

## 📊 Análises Realizadas
1. **Faturamento Total por Loja** – Identificação das lojas mais lucrativas.  
2. **Vendas por Categoria** – Distribuição das vendas entre os diferentes segmentos de produtos.  
3. **Avaliação Média dos Clientes** – Indicador de satisfação e qualidade percebida.  
4. **Produtos Mais e Menos Vendidos** – Itens de maior e menor giro comercial.  
5. **Frete Médio por Loja** – Competitividade nos custos de entrega.  
6. **Gráficos de Apoio** – Visualizações para reforçar as conclusões.  

---

## 📈 Resultados
- **Loja 1 e Loja 2** → Mais vantajosas, com alto faturamento, boas avaliações e frete competitivo.  
- **Loja 3** → Desempenho intermediário, aceitável para manutenção.  
- **Loja 4** → Menos vantajosa:  
  - Menor faturamento.  
  - Categorias de baixo valor agregado.  
  - Pior avaliação média dos clientes.  
  - Frete médio mais alto.  

📌 **Recomendação:** **Vender a Loja 4** e investir os recursos em novos projetos.  

---

## 📎 Como Executar
1. Clone o repositório ou baixe os arquivos.  
2. Certifique-se de ter o **Python 3.10+** instalado.  
3. Instale as bibliotecas necessárias:  
   ```bash
   pip install pandas matplotlib seaborn
