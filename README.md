# 🛍️ Análise de Desempenho de Lojas - Projeto de Data Science

![Status](https://img.shields.io/badge/status-concluído-brightgreen)  
![Python](https://img.shields.io/badge/python-3.11-blue)  
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## 📌 Sobre

Este projeto de análise de dados foi desenvolvido como parte de um **desafio da formação Data Science da Alura**, com o objetivo de analisar o desempenho de 4 lojas e recomendar **qual loja possui o menor desempenho, e deve ser vendida** com base em critérios como faturamento, satisfação de clientes, logística, valor do frete, e popularidade dos produtos.

---

## ⚙️ Tecnologias e Bibliotecas Utilizadas

- **Python 3.11**
- `Pandas` - Manipulação de dados
- `Matplotlib` - Visualização gráfica
- `Seaborn` - Gráficos estatísticos avançados
- `Folium` - Geração de mapas interativos
- `Plotly` - Gráficos dinâmicos 

---

## 📊 Etapas da Análise

### 1. 📦 Faturamento Total por Loja
- Soma dos valores da coluna **Preço** para estimar o desempenho financeiro.
- Gráfico de **barras** estilizado para facilitar a comparação.

### 2. 🧮 Categorias Mais Vendidas
- Agrupamento por **Categoria do Produto**.
- Visualização por loja para entender preferências de consumo.

### 3. ⭐ Avaliações Médias
- Análise da coluna **Avaliação da compra**.
- Gráfico de **pontos** para representar visualmente.

### 4. 🔝 Produtos Mais e Menos Vendidos
- Contagem de frequência dos produtos por loja.
- Gráfico de **violino** para representar a variação.

### 5. 🚚 Frete Médio
- Cálculo da média da coluna **Frete** por loja.
- Representação com **linhas**.

### 6. 🗺️ Análise Geográfica
- Uso de **Latitude e Longitude** para mapear as compras.
- Gráfico de **dispersão por loja** para visualização de distribuição regional.

---

## 💡 Como Executar o Projeto

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/projeto-analise-lojas.git
```

2. Instale os pacotes necessários:

```bash
pip install -r requirements.txt
```

3. Execute o notebook:

```bash
jupyter notebook analise_lojas.ipynb
```

---

## ❗ Possíveis Problemas

- Certifique-se de estar usando a **versão correta do Python (3.11 ou superior)**.
- Os dados são carregados diretamente de URLs, então uma conexão com a internet é necessária.
- Algumas bibliotecas como `folium` podem não funcionar corretamente em ambientes offline.

---

## ✍️ Autor

Projeto desenvolvido por [Eduarda "Towacchi" Brites](https://github.com/Towacchi)

---
