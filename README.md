Analisando os dados e construindo um modelo de regressão linear com Python no Google Colab. 

Contexto - Para ampliar sua base de clientes e impulsionar as vendas, uma empresa de marketing investe mensalmente em publicidade online, utilizando plataformas como YouTube, Facebook e 
Newspaper para captar leads e impulsionar as vendas. Para garantir a eficiência desses investimentos, registramos os custos e analisamos os retornos, permitindo a otimização contínua das 
campanhas. A empresa espera que o especialista em dados analise os fatores que influenciam a geração de leads e desenvolva um modelo preditivo para estimar o retorno de vendas com base nos 
investimentos em publicidade.

Os dados representam investimentos em publicidade em três plataformas — YouTube, Facebook e newspaper — e suas respectivas vendas (sales).

Quantidade de registros: 171 linhas. Média: O investimento médio foi de 178,02 no YouTube, 27,67 no Facebook e 35,24 em jornais, resultando em uma média de 16,92 vendas. 
Desvio padrão (std): O YouTube tem a maior variação nos investimentos 102,45, enquanto newspaper e Facebook apresentam menor dispersão (24,90 e 17,91, respectivamente). 
Mínimos e máximos: O investimento mínimo foi próximo de zero em todas as plataformas, enquanto os valores máximos foram 355,68 no YouTube, 59,52 no Facebook e 121,08 em jornais. 
As vendas variaram entre 1,92 e 32,4. Quartis: 50% dos dados estão distribuídos entre 91,08 e 262,98 (YouTube), 11,7 e 43,68 (Facebook), 13,74 e 50,88 (jornais) e 12,54 a 20,82 (vendas), 
indicando uma maior concentração dos investimentos e das vendas dentro desses intervalos.

Youtube é a variável mais relevante para prever Sales. O forte coeficiente de correlação (0.782) sugere que investir no Youtube está altamente associado ao aumento das vendas. 
Facebook também é importante, mas menos que Youtube. A correlação moderada (0.602) indica que o investimento nessa plataforma tem impacto positivo nas vendas, 
mas não tão significativo quanto o Youtube. Newspaper tem influência fraca. A correlação baixa (0.255) sugere que o investimento em Jornal tem pouco efeito sobre as vendas. 
Se o objetivo for maximizar vendas, o foco principal deve estar no investimento em Youtube, seguido de Facebook, enquanto o impacto de Newspaper é mais limitado.

Modelagem de dados / Separando as variáveis: x contém as variáveis explicativas. y contém a variável-alvo.

Objetivo: Prever as vendas com base nos investimentos em youtube, facebook e newspaper. Aqui, x seria usado como entrada para um modelo de regressão e y seria o valor a ser previsto.

Conclusão: De acordo com o resultado obtido, a comparação entre um alto investimento no YouTube e um baixo investimento em Newspaper sugere que as vendas tendem a ser altas, 
com projeções mais positivas. Por outro lado, quando há um alto investimento em Newspaper e um baixo investimento no YouTube, as vendas apresentam uma queda drástica, 
com uma redução de 77,7% nas vendas comparando a primeira projeção com a segunda. Nos testes o Facebook se mostra positivo, porém não tão positivo quanto o Youtube.
