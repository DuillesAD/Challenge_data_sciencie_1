
# Análise de Vendas - Alura Store

## 📌 Propósito da análise realizada

O objetivo desta análise é entender o comportamento de vendas da loja virtual Alura Store. Foram examinados os dados de pedidos realizados, itens comprados, preferências por categorias de produtos e comportamento de compra por dispositivo (desktop ou mobile). A análise fornece insights valiosos sobre o desempenho da loja e o perfil dos consumidores.

## 📂 Estrutura do projeto e organização dos arquivos

```
📁 AluraStoreAnalysis
│
├── 📄 AluraStoreBr.ipynb       # Notebook com toda a análise exploratória
├── 📄 README.md                # Este arquivo explicativo
└── 📁 dados                    # (opcional) Pasta para armazenar conjuntos de dados CSV, se houver
```

O notebook está estruturado da seguinte forma:
1. **Importação de bibliotecas e leitura dos dados**
2. **Visualização básica do DataFrame**
3. **Análise de categorias de produtos mais vendidos**
4. **Comparação entre dispositivos (desktop vs mobile)**
5. **Gráficos explicativos sobre comportamento de compra**

## 📊 Exemplos de gráficos e insights obtidos

Durante a análise foram gerados diversos gráficos com `matplotlib` e `seaborn`. Alguns insights relevantes incluem:

- 📈 **Categorias mais vendidas**: Cursos da categoria `Front-end` e `Data Science` lideram em número de pedidos.
- 📉 **Taxa de abandono por dispositivo**: Dispositivos móveis apresentam maior abandono de carrinho em relação ao desktop.
- 🛒 **Conversão por categoria**: Algumas categorias têm alta taxa de visualização, mas baixa conversão.
  
Exemplos de gráficos incluídos:
- Gráfico de barras com o número de pedidos por categoria
![image](https://github.com/user-attachments/assets/ee43bc55-8e5c-4a3d-8d54-d5eafc7bb2ce)

- Gráfico de comparação de taxas de abandono por tipo de dispositivo
- Gráficos de conversão de compra vs. visualização por categoria

## ⚙️ Instruções para executar o notebook

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/AluraStoreAnalysis.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd AluraStoreAnalysis
   ```
3. Instale os pacotes necessários (use um ambiente virtual, se preferir):
   ```bash
   pip install pandas matplotlib seaborn
   ```
4. Execute o notebook com Jupyter:
   ```bash
   Colab notebook AluraStoreBr.ipynb
   ```
