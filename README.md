# 📊 Projeto MAPA - Análise de Padrões de Comportamento de Compra

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte de uma atividade acadêmica da disciplina de Reconhecimento de Padrões.

O objetivo é analisar uma base de dados simulada de compras para identificar padrões de comportamento dos clientes, considerando características como idade, sexo, produto comprado, preço, horário e dia da semana.

## 🎯 Objetivo

Identificar e interpretar padrões de comportamento de compra a partir dos dados disponíveis.

Foram analisadas relações entre:

- 👥 Faixa etária
- ⚥ Sexo
- 🛍️ Produto comprado
- 💰 Valor da compra
- 🕐 Horário da compra
- 📅 Dia da semana

## 🛠️ Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## 📂 Arquivo do projeto

O código completo da análise está disponível no notebook:

**`projeto_MAPA.ipynb`**

O notebook contém a criação da base, tratamento e organização dos dados, análises estatísticas, identificação dos padrões e visualização gráfica.

## 🔎 Principais análises

### 👥 Faixa etária

Os clientes foram classificados em três grupos:

| Faixa etária | Valor médio das compras |
|---|---:|
| Jovens | R$ 243,33 |
| Adultos | R$ 169,95 |
| Mais de 40 anos | R$ 2.240,00 |

Na base analisada, os clientes com mais de 40 anos apresentaram o maior valor médio de compra.

### 🕐 Período do dia

| Período | Valor médio das compras |
|---|---:|
| Manhã | R$ 949,93 |
| Tarde | R$ 1.373,33 |
| Noite | R$ 290,00 |

A tarde apresentou o maior valor médio de compra entre os períodos analisados.

### ⚥ Sexo

| Sexo | Valor médio das compras |
|---|---:|
| Feminino | R$ 865,98 |
| Masculino | R$ 759,98 |

Na base analisada, as mulheres apresentaram um valor médio de compra ligeiramente superior ao dos homens.

### 📅 Dia da semana

A análise também considerou a quantidade e o valor das compras realizadas em cada dia da semana.

A quarta-feira apresentou o maior valor total de compras, com **R$ 3.559,90**, enquanto o domingo apresentou o maior valor médio, de **R$ 2.700,00**.

É importante observar que a base possui apenas 10 registros. Portanto, os resultados representam os dados analisados e não devem ser generalizados para todos os consumidores.

## 📈 Visualização

O projeto apresenta um gráfico relacionando a faixa etária dos clientes com o valor médio das compras.

O gráfico pode ser visualizado no arquivo:

**`grafico_faixa_etaria.png`**

## 📊 Principais resultados

A análise permitiu identificar alguns padrões na base simulada:

1. Clientes com mais de 40 anos apresentaram valores médios de compra mais elevados.
2. As compras realizadas durante a tarde apresentaram o maior valor médio.
3. As mulheres apresentaram uma média de compra ligeiramente superior à dos homens.
4. Os valores das compras variaram bastante entre os diferentes perfis de clientes.

## 📚 Conclusão

A análise dos dados permitiu identificar diferentes padrões de comportamento de compra entre os clientes.

Os resultados mostram que características como faixa etária, horário e sexo podem apresentar diferenças nos valores das compras. Entretanto, devido ao pequeno tamanho da base, os resultados devem ser interpretados com cautela.

Em uma situação real, uma base de dados maior permitiria identificar padrões mais confiáveis e auxiliar empresas na criação de estratégias de vendas, segmentação de clientes e tomada de decisões baseada em dados.

---

**Projeto desenvolvido para fins acadêmicos.**
