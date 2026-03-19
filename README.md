# 📊 Desafio Mconf – Análise de Dados (Base Olist)

## 📌 Sobre o projeto

Este projeto apresenta uma análise exploratória da base de dados pública da Olist, com foco na identificação de padrões, inconsistências e oportunidades de negócio.

A análise foi desenvolvida no Google Colab, utilizando Python e bibliotecas de análise de dados para explorar o comportamento dos clientes, qualidade dos dados e distribuição geográfica.

---

## 🎯 Objetivo

* Avaliar a qualidade e integridade dos dados
* Identificar padrões de comportamento dos clientes
* Detectar inconsistências entre bases
* Gerar insights estratégicos para crescimento do negócio

---

## 🛠️ Tecnologias utilizadas

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Google Colab

---

## ▶️ Como executar

Clique abaixo para abrir o notebook:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1EPyGNjaqEnnRqpugaYwTmq_7YEUzPR_w)

---

## 🔍 Etapas da análise

### 1. Entendimento dos dados

* Identificação das entidades principais (clientes, pedidos, geolocalização)
* Análise de cardinalidade e relações

### 2. Limpeza e tratamento

* Verificação de valores nulos
* Padronização de dados
* Identificação de inconsistências

### 3. Análise exploratória

* Distribuição geográfica
* Volume de pedidos
* Comportamento temporal

### 4. Geração de insights

* Diagnóstico da base
* Oportunidades de crescimento
* Recomendações estratégicas

---

## 📈 Principais insights

### 📊 Volume e comportamento dos clientes

* Foram identificados **99.441 pedidos únicos** e **96.096 clientes únicos**
* Aproximadamente **3.300 clientes realizaram mais de uma compra**, indicando recorrência na plataforma

---

### ⚠️ Qualidade dos dados

* A base de clientes não apresenta valores nulos
* A base de pedidos possui **2.965 registros sem data de entrega**, indicando possíveis falhas logísticas ou operacionais
* Esses registros representam pedidos com impedimentos no fluxo de entrega

---

### 🌎 Distribuição geográfica

* O estado de **São Paulo concentra quase metade dos pedidos**, evidenciando forte dependência regional
* A base de geolocalização apresenta mais de **1 milhão de registros**, porém com **8.011 cidades únicas**, número superior aos **5.570 municípios oficiais do Brasil**
* Isso indica problemas de padronização, como:

  * erros de digitação
  * variações de escrita
  * duplicidade de cidades

---

### 🔗 Problemas de integração entre bases

* Foi observada uma perda de aproximadamente **0,73% dos registros** no processo de junção entre tabelas
* O problema está associado a inconsistências na escrita de cidades (ex: “mogi-guacu” vs “mogi guaçu”)

💡 **Recomendação:**

* Utilizar **CEP como chave de integração**, por ser um identificador padronizado e menos suscetível a erros

---

### 🚀 Oportunidades de crescimento

* Baixa penetração da plataforma no **Norte e Nordeste**
* Destaques:

  * **São José de Ribamar**: 245 mil habitantes e apenas 14 clientes
  * **Manaus**: mais de 2,1 milhões de habitantes com baixa presença
  * Outras cidades relevantes: Marabá, Parauapebas, Juazeiro do Norte

👉 Indica alto potencial de expansão fora do eixo tradicional

---

### 📍 Padrão de distribuição

* Forte concentração de clientes no **litoral do Sudeste**
* Interior do país apresenta baixa cobertura → oportunidade clara de crescimento

---

### 📅 Comportamento temporal

* Crescimento consistente da plataforma até 2017
* Pico de vendas durante a **Black Friday**
* Maior volume de compras ocorre entre **10h e 22h**, com pico no período da tarde

💡 **Aplicação prática:**

* Melhor horário para campanhas e anúncios

---

## ⚠️ Limitações

* Dados com inconsistências de padronização
* Falta de contexto operacional mais detalhado
* Dependência da qualidade da base fornecida

---

## 🚀 Possíveis melhorias

* Padronização de dados geográficos
* Uso de identificadores únicos (como CEP)
* Criação de dashboards interativos
* Aplicação de modelos preditivos para expansão de mercado

---

## 👤 Autor

**César Yuri Silva Santos**
