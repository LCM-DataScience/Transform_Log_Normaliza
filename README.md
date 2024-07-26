🔀 Estatística - Estudo de Caso:

Transformação Logarítmica, Normalização e Outras Transformações


🔎 Necessidade técnica:

No mercado financeiro, diferentes ativos podem ter ordens de grandeza distintas, dificultando comparações diretas. Para resolver esse problema, utilizamos transformações de dados, que melhoram a visualização e interpretação dos resultados.


1️⃣ Transformação Logarítmica:

✅ Aplicação prática: Aqui é utilizado o logaritmo natural (ln(x)) para transformar os valores do S&P 500 e IBOVESPA, que possuem magnitudes distintas. Essa transformação facilita a comparação direta, trazendo os valores para uma escala linear. 


🔎 Características do Logaritmo Natural:

Calculado com base no número irracional (e), aproximadamente 2,71828, suas propriedades ajudam a converter grandes variações em valores mais comparáveis, transformando distribuições nominais em distribuições mais lineares.


2️⃣ Normalização

✅ Aplicação prática: Neste exemplo, os dados obstidos de S&P 500 e IBOVESPA são divididos por seus valores iniciais, trazendo ambos os índices para uma base comum e facilitando a análise comparativa.


3️⃣ Padronização (Scale)

✅ Aplicação prática: Os dados de volume de negociação obtidos das ações VALE3, PETR4 e ITUB4 possuem magnitudes muito diferentes. Após a aplicação da padronização, todos os dados são transformados para uma distribuição com média zero e variância um. Isso significa que as diferenças de escala são eliminadas.


4️⃣ Transformação MIN-MAX

✅ Aplicação prática: Seguindo o mesmo racional, os dados de volume de negociação originais apresentam grandezas distintas. Essa transformação é feita subtraindo o valor mínimo e dividindo pelo intervalo (diferença entre o valor máximo e o mínimo)


5️⃣ Binarização

✅ Aplicação prática: No exemplo aplicado, os dados de variação percentual diária do milho são contínuos e podem apresentar uma ampla gama de valores. Com a binarização, podemos definir o limiar como 1%, tornando os valores acima de 1% como 1 e os valores abaixo de 1% como 0; Ao invés de trabalharmos com uma gama de valores percentuais, agora temos melhor definido se as variações diárias do milho superam ou não o limiar de 1%.


🔆 Conclusão

Ao aplicar essas técnicas, conseguimos realizar comparações mais diretas entre ativos com escalas distintas:


Inicialmente, os dados nominais dos índices mostram uma grande disparidade, dificultando a comparação. Após a transformação logarítmica, os dados foram trazidos para uma escala linear, permitindo uma comparação mais clara das tendências.


Com a normalização e as outras transformações, foi possível unificar as escalas dos dados, destacar as flutuações em torno da média, ajustar os dados para um intervalo fixo e destacar variações significativas.
