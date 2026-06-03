<div align="center">
  
# Operações B2C com foco em dados

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#) [![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab&logoColor=fff)](#)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=fff)](#)

</div>

**Palavras-chave**: `crédito`. `dados`. `operações b2c`.

<div align="center">

[Objetivo](#-objetivo) | [Descrição do problema](#-descrição-do-problema) | [Linguagem e IDE utilizados](#-linguagem-e-IDE-utilizados) | [Bibliotecas](#-bibliotecas) | [Construção da solução](#-construção-da-solução) | [Conclusões](#-conclusões)

</div>

---

## 🎯 Objetivo

O objetivo deste documento é apresentar de forma resumida o processo de solução da Prova técnica - Operações B2C com foco em dados para o processo seletivo de Analista de Operações I do Agibank. O intuito da prova é avaliar o raciocínio analítico, organização lógica e uso de ferramentas de dados, automação e IA.

---

## 📝 Descrição do problema

Você está atuando na área de operações B2C de uma instituição financeira. Diariamente recebemos bases com solicitações de clientes que precisam ser tratadas e transformadas em controles operacionais e análises. Foi fornecido o dataset `Base dados Prova Técnica.csv` (disponível neste repositório) que serviu de base para elaboração desse trabalho. Foi possível verificar que a base dados apresenta indicadores do `mercado de crédito` (cartões, empréstimos e financiamentos) da instituição financeira.

---

## 🐍 Linguagem e IDE utilizados

A linguagem escolhida foi o **Python**, pois possuo mais familiaridade com os recursos, bibliotecas e IDE, trabalho há mais tempo com elas e tenho maior facilidade de escrever códigos nela; acredito que é mais intuitiva e permite fácil compartilhamento e compreensão dos scripts. Além disso, na minha pós em Engenharia Financeira todos os projetos e tarefas de análise de dados aplicados em finanças foram feitas quase que exclusivamente usando Python. A IDE utilizada é o [Google Colab](https://colab.research.google.com/), uma extensão (ou "spin-off") do Jupiter da empresa Anaconda. Essa escolha baseia-se no fato que o Colab possui integração com a IA Gemini da Google, facilitando e otimizando o trabalho de escrita do código.

---

## 📚 Bibliotecas

Basicamente usamos apenas o [Pandas](https://pandas.pydata.org/) para organização e manipulação de dados mas. para evitar erros de compilação, adicionamos o [NumPy](https://pandas.pydata.org/) para funções matemáticas e operações com arrays (vetores e matrizes) que são a base das estrtuturas tabulares do Pandas. O [Matplotlib](https://matplotlib.org/stable/) é um extra para esse projeto, mas é extremamente útil para visualizar tendências e padrões, fornecendo uma camada gráfica que ajuda na interpretação, comunicação e análise dos dados.

---

## 👷🏻 Construção da solução

A construção do código solução deste teste é bem straightforward; começamos com a criação do drive virtual que armazena o arquivo do dataset. Essa etapa pode ser opcional, mas como o Colab apaga os arquivos ao encerrar uma sessão, queríamos ter acesso permanente ao .csv sem a necessidade de upload em cada novo acesso, otimizando tempo para a programação.

A seguir seguimos com a importação das bibliotecas de análise, Pandas, NumPy e Matplotlib, tal como descrevemos na seção anterior.

Na sequência, as etapas subsequentes de solução são bem lineares e de acordo com o roteiro disponível no arquivo `Prova_Técnica.docx` deste repositório. Basicamente seguimos a ordem lógica do trabalho do `analista de dados`: 

```python
1. coleta/extração 
2. análise preliminar
3. limpeza, formatação e validação, 
4. obtenção de métricas estatísticas globais
5. cálculo e extração de indicadores de desempenho
6. análise dos dados em si (storytelling, significado e impactos dos indicadores) 
```

---

## ✅ Conclusões

A partir da análise realizada foi possível apresentar insights relevantes e estratégicos do mercado de crédito da instituição financeira, bem como propor melhorias globais de processos. Conseguimos ir além do objetivo inicial, pois através dos dados mostramos sugestões de **direcionamento de ações comerciais**, tais como: i) abordagem de clientes com potencial de negócios; ii) ampliação da base via ações de marketing digital e iii) fortalecimento dos canais de oferta dos produtos de crédito. Por fim, discutimos como utilizar LLMs e IAs em nosso dia-a-dia para automatizar e otimizar o trabalho do analista do dados.

---
