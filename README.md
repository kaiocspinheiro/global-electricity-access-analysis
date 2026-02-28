# 🌍 Análise Global do Acesso à Eletricidade (2000–2024)

## 📌 Contexto

Este conjunto de dados reúne indicadores do Banco Mundial ao longo de 25 anos, permitindo analisar a relação entre desenvolvimento econômico, dinâmica populacional e acesso à eletricidade em nível global.

O objetivo desta análise é identificar padrões e desigualdades entre países.

Dataset inspirado no projeto de Muhammad Aammar Tufail, desenvolvido com abordagem própria para fins de estudo.

---

## 📊 Estrutura da Análise

- 4.880 linhas  
- 9 colunas  
- Período: 2000 a 2024  

### 🔎 Verificação de Dados
![EDA](images/1.png)

---

# 1️⃣ Panorama Global do Acesso à Eletricidade

## 1.1 - Quantos países tinham 100% de acesso em 2015?

**69 países** possuíam acesso urbano e rural universalizado em 2015.

---

## 1.2 - Tendência média global do acesso rural (2000–2016)

![Tendência Rural](images/2.png)

Entre 2000 e 2016:

- 2000: 68,63%
- 2016: 78,77%
- Crescimento: +10,14 p.p.

Observa-se crescimento consistente, com aceleração após 2011.

---

## 1.3 - Países com maior crescimento rural

![Crescimento Rural](images/3.png)

Destaques:

- Bhutan (+86 p.p.)
- Nepal (+66,4 p.p.)
- Marshall Islands (+65,9 p.p.)

Predominância de países africanos e do Sul da Ásia.

---

## 1.4 - Maior disparidade urbano x rural

![Disparidade](images/4.png)

- Média global em 2016: 14,2 p.p.
- Mali, Guiné e Camarões: >50 p.p.

Ainda existem desigualdades estruturais significativas.

---

# 2️⃣ Energia e Desenvolvimento Econômico

## 2.1 - Top 10 PIB per capita (2023)

![Top PIB](images/5.png)

Concentração na Europa Ocidental e centros financeiros globais.

---

## 2.2 - Correlação PIB x Acesso

![Correlação](images/6.png)

- Rural: r = 0,47 (moderada)
- Urbana: r = 0,37 (mais fraca)

Renda influencia, mas não é determinante isolada.

---

## 2.3 - Existe um PIB mínimo para universalização?

![Threshold PIB](images/7.png)

Não há threshold fixo.  
Fatores institucionais e tecnológicos influenciam o processo.

---

# 3️⃣ Demografia e Infraestrutura

## 3.1 - Crescimento populacional global

![População](images/8.png)

- 2000: 5,7 bilhões
- 2024: 7,4 bilhões
- +1,7 bilhão no período

---

## 3.2 - Produção de eletricidade x População

![Produção vs População](images/9.png)

Correlação positiva estrutural, com padrão linear em escala logarítmica.

---

## 3.3 - Crescimento populacional x Expansão do acesso

![Crescimento Pop](images/10.png)

Não há relação clara entre crescimento demográfico e expansão do acesso rural.

---

# 🛠 Ferramentas Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Pycountry
- Jupyter Notebook