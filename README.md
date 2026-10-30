# Tech Challenge Fase 1 - NPS Preditivo

## Objetivo

Identificar os principais fatores que influenciam a satisfação dos clientes de um e-commerce e propor uma abordagem analítica capaz de antecipar sinais de insatisfação a partir de informações operacionais já disponíveis na empresa.

---

## Contexto do Negócio

Com o crescimento do e-commerce, a empresa passou a enfrentar desafios relacionados à experiência dos clientes e à capacidade de monitorar sua satisfação.

Embora o Net Promoter Score (NPS) seja amplamente utilizado para mensurar a satisfação, nem todos os clientes respondem às pesquisas. Nesse contexto, o objetivo deste projeto é compreender quais fatores operacionais influenciam o NPS e como a Ciência de Dados pode auxiliar na identificação antecipada de clientes com maior risco de insatisfação.

---

## Base de Dados

A base utilizada neste projeto contém 2.500 registros relacionados à experiência de clientes em um ambiente de e-commerce.

Os dados contemplam:

- Perfil dos clientes;
- Informações dos pedidos;
- Indicadores logísticos;
- Indicadores de atendimento;
- Métricas de satisfação (CSAT e NPS).

A variável alvo utilizada ao longo das análises foi:

```text
nps_score
```

representando o nível de satisfação dos clientes após a jornada de compra.

---

## Metodologia

O projeto foi desenvolvido seguindo a metodologia CRISP-DM:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Exploratory Data Analysis (EDA)
5. Modelagem Preditiva (Opcional)
6. Storytelling e Recomendações

---

## Principais Insights

As análises exploratórias permitiram identificar os principais fatores associados à satisfação dos clientes.

Principais achados:

- O atraso na entrega foi o fator operacional mais associado à redução do NPS;
- Clientes com maior quantidade de reclamações tendem a apresentar níveis inferiores de satisfação;
- Clientes que precisam interagir frequentemente com o atendimento tendem a relatar experiências menos satisfatórias;
- Foi identificado um possível ponto de ruptura na experiência a partir de aproximadamente 4 a 5 dias de atraso;
- Clientes mais satisfeitos apresentam maior probabilidade de recompra;
- Os fatores operacionais mostraram maior influência sobre o NPS do que características financeiras dos pedidos.

---

## Estrutura do Projeto

```text
data/
├── desafio_nps_fase_1.csv
├── dicionario_dados.md

images/
├── 01_distribuicao_nps.png
├── 02_heatmap_correlacao.png
├── 03_impacto_atrasos_nps.png
├── 04_impacto_reclamacoes_nps.png
├── 05_nps_medio_por_atraso.png
├── 06_nps_regiao.png
├── 07_recompra_vs_nps.png

notebooks/
├── 01_EDA_ExploraçãoInicial.ipynb

reports/
├── Tech Challenge - Fase 1 (Case NPS Preditivo)_V2.pdf
├── Gravação de Tech Challenge - Fase 1 (Case NPS Preditivo) - V2.mp4
├── Video_Apresentacao.txt

```

---

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab
- GitHub

---

## Como Reproduzir a Análise

### 1. Clone o repositório

```bash
git clone https://github.com/GabsBk/postech-ai-scientist-fase1-nps
```

### 2. Instale as dependências

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3. Execute o notebook

Abra o notebook localizado na pasta:

```text
notebooks/
```

e execute as células em sequência.

---

## Resultados Esperados

Ao final da execução será possível:

- Compreender o comportamento geral do NPS;
- Identificar os principais fatores associados à satisfação;
- Avaliar o impacto de atrasos e reclamações;
- Identificar potenciais detratores;
- Entender a relação entre satisfação e recompra;
- Apoiar recomendações estratégicas para melhoria da experiência do cliente.

---

## Materiais para Avaliação

### Notebook de Análise

```text
notebooks/01_EDA_ExploraçãoInicial.ipynb
```

### Apresentação

```text
reports/Tech Challenge - Fase 1 (Case NPS Preditivo)_V2.pdf
```

### Vídeo da Apresentação Executiva

```text
reports/Gravação de Tech Challenge - Fase 1 (Case NPS Preditivo) - V2.mp4
```

Informações adicionais também podem ser encontradas em:

```text
reports/Video_Apresentacao.txt
```

---

## Integrantes

- Gabriel dos Santos Camilo
- Rodolfo Gabriel Vieira
- Kauê Henrique dos Santos
- Guilherme Mendes Machado

---

## Licença

Projeto desenvolvido exclusivamente para fins acadêmicos na Pós-Tech FIAP - AI Scientist.
