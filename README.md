# global-electricity-access-analysis

Análise Global do Acesso à Eletricidade (2000–2024)
Contexto

Este conjunto de dados reúne indicadores do Banco Mundial ao longo de 25 anos, permitindo analisar a relação entre desenvolvimento econômico, dinâmica populacional e acesso à eletricidade em nível global.

O objetivo desta análise é identificar padrões e desigualdades entre países.

Dataset inspirado no projeto de Muhammad Aammar Tufail, esta análise foi desenvolvida com abordagem própria para fins de estudo e aprofundamento em análise de dados.

Estrutura da Análise

O dataset contém: 4880 linas e 9 colunas

Período: 2000 a 2024

## 1. Panorama Global do Acesso à Eletricidade
1.1 - Quais países tinham 100% de acesso à eletricidade (urbano e rural) em 2015?

Identificação dos países com universalização completa do acesso, permitindo avaliar padrões regionais e níveis de desenvolvimento associados.

1.2 - Qual é a tendência média global de acesso à eletricidade rural (2000–2016)?

Entre 2000 e 2016, observa-se tendência claramente crescente no acesso médio global à eletricidade rural.

2000: ~68,63%

2016: ~78,77%

Crescimento total: +10,14 pontos percentuais

O crescimento foi relativamente consistente, com leve aceleração após 2011, possivelmente refletindo investimentos em infraestrutura e políticas públicas voltadas à eletrificação rural.

1.3 - Quais países apresentam o crescimento mais rápido em eletricidade rural?

Os maiores crescimentos ocorreram majoritariamente em países em desenvolvimento, com destaque para:

Bhutan (+86 p.p.)

Nepal (+66,4 p.p.)

Marshall Islands (+65,9 p.p.)

Observa-se forte presença de países africanos e do Sul da Ásia, sugerindo expansão significativa da infraestrutura elétrica em economias que partiam de níveis historicamente baixos.

1.4 - Quais países têm maior disparidade entre acesso urbano e rural?

Em 2016, a média global da disparidade urbano-rural foi de aproximadamente 14,2 pontos percentuais.

Entretanto, países como Mali, Guiné e Camarões apresentam diferenças superiores a 50 p.p., evidenciando forte concentração da infraestrutura nas áreas urbanas.

1.5 - A desigualdade urbano-rural está diminuindo ao longo do tempo?

A análise temporal indica redução gradual da desigualdade média global, embora persistam diferenças significativas em países de baixa renda.

## 2. Energia e Desenvolvimento Econômico
2.1 - Quais são os 10 principais países por PIB per capita em 2023?

Os países com maior PIB per capita concentram-se majoritariamente na Europa Ocidental.

Esses países apresentam infraestrutura energética universalizada e baixos níveis de disparidade no acesso.

2.2 - Existe correlação entre PIB per capita e acesso à eletricidade?

Observa-se:

Correlação moderada positiva entre PIB per capita e acesso rural (r = 0,47)

Correlação mais fraca entre PIB e acesso urbano (r = 0,37)

Isso sugere que renda influencia a expansão rural, mas não é o único fator determinante.

2.3 - Existe um nível de PIB a partir do qual o acesso tende a ser universal?

A evolução do PIB mínimo entre países com acesso universal não segue padrão linear.

Início dos anos 2000: países com renda relativamente baixa já apresentavam universalização.

2006–2012: concentração em economias de renda média.

Pós-2013: redução do nível mínimo necessário.

Conclusão: não há um threshold fixo de PIB para universalização; fatores institucionais e tecnológicos também desempenham papel relevante.

## 3. Demografia e Infraestrutura
3.1 - Como a população global mudou (2000–2024)?

A população global cresceu de aproximadamente:

5,7 bilhões (2000)

7,4 bilhões (2024)

Aumento total: +1,7 bilhão de pessoas.

O crescimento foi contínuo e relativamente estável.

3.2 - Como a produção de eletricidade se relaciona com a população?

Observa-se correlação positiva entre população e produção total de eletricidade.

Países mais populosos tendem a produzir maior volume absoluto de energia.

Em escala logarítmica, a relação apresenta padrão aproximadamente linear, indicando estrutura consistente entre tamanho populacional e demanda energética.

3.3 - Países com crescimento populacional alto conseguem expandir acesso?

Não há relação clara entre crescimento populacional e expansão do acesso rural.

Os resultados variam significativamente entre países, indicando que crescimento demográfico isoladamente não explica a evolução da infraestrutura elétrica.

## Ferramentas Utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

Pycountry

Jupyter Notebook
