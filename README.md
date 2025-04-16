# 🛍️ Análise de Desempenho de Lojas - Projeto de Data Science

![Status](https://img.shields.io/badge/status-concluído-brightgreen)  
![Python](https://img.shields.io/badge/python-3.11-blue)  
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## 📌 Sobre o Projeto

Este projeto de análise de dados foi desenvolvido como parte de um **desafio de Data Science**, com o objetivo de analisar o desempenho de 4 lojas e recomendar **qual loja o Senhor João deve vender** com base em critérios como faturamento, satisfação de clientes, logística e popularidade dos produtos.

---

## ⚙️ Tecnologias e Bibliotecas Utilizadas

- **Python 3.11**
- `Pandas` - Manipulação de dados
- `Matplotlib` - Visualização gráfica
- `Seaborn` - Gráficos estatísticos avançados
- `Folium` - Geração de mapas interativos
- `Plotly` - Gráficos dinâmicos (opcional)

---

## 📊 Etapas da Análise

### 1. 📦 Faturamento Total por Loja
- Soma dos valores da coluna **Preço** para estimar o desempenho financeiro.
- Gráfico de barras estilizado para facilitar a comparação.

### 2. 🧮 Categorias Mais Vendidas
- Agrupamento por **Categoria do Produto**.
- Visualização por loja para entender preferências de consumo.

### 3. ⭐ Avaliações Médias
- Análise da coluna **Avaliação da compra**.
- Gráfico de **circular (pie chart)** para representar visualmente.

### 4. 🔝 Produtos Mais e Menos Vendidos
- Contagem de frequência dos produtos por loja.
- Gráfico de **boxplot estilizado** para representar a variação.

### 5. 🚚 Frete Médio
- Cálculo da média da coluna **Frete** por loja.
- Representação com **gráfico de linha suave (lineplot)**.

### 6. 🗺️ Análise Geográfica
- Uso de **Latitude e Longitude** para mapear as compras.
- Gráfico de **dispersão por loja** para visualização de distribuição regional.

---

## ✅ Conclusão e Recomendação Final

Após uma análise detalhada dos dados de vendas, frete, avaliações e distribuição geográfica, foi recomendado que o **Senhor João venda a loja 3, por possuir menor desempenho**.

### 🧾 Justificativa:

- 📉 **Menor faturamento** entre as quatro lojas.
- ⭐ **Avaliações mais baixas** dos clientes.
- 🚚 **Frete médio mais alto**, indicando possíveis gargalos logísticos.
- 🧊 **Baixa variedade e venda por categoria**.
- 🗺️ **Distribuição geográfica menos abrangente**.

Esses fatores combinados indicam que essa loja tem menos potencial de crescimento e pode representar um custo de oportunidade maior.

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
