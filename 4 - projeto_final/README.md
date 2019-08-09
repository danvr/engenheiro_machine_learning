# Otimização de Campanha de Marketing via Clusterização e Regressão 

O objetivo do projeto é aplicar o aprendizado obtido durante o programa de Nanodegree Engenheiro de Machine Learning para solucionar um problema na área do Marketing Digital aplicando algoritmos e técnicas de Machine Learning para Segmentação de Clientes.

#### Conjunto de Dados e Inputs

Os dados usados neste projeto foram encontrados no banco de dados da kaggle para informações e download do dataset está [aqui.](https://www.kaggle.com/loveall/clicks-conversion-tracking) Os dados se referem a uma da campanha publicitária de mídia social de uma organização anônima. O Dataset contém 1143 observações (Linhas) em 11 variáveis (Colunas). Abaixo estão as descrições das variáveis:

- **ad_id:** ID exclusivo para cada anúncio;
- **xyz_campaign_id:** ID associado a cada campanha publicitária empresa XYZ;
- **fb_campaign_id:** ID associado a campanha como o facebook rastreia a camapanha;
- **age:** Idade da pessoa a quem o anúncio foi mostrado;
- **gender:** Gênero da pessoa a quem o anúncio foi mostrado;
- **interest:** Código que especifica a categoria de qual o interesse da pessoa pertence;
- **Impressions:** Numero de vezes que aunncio foi mostrado;
- **Clicks:** Número de cliques do anuncio;
- **Spent:** Quantidade pago pela empresa XYZ para o Facebook, para mostrar o anúncio;
- **Total conversion:** Número total de pessoas que se interessaram sobre o produto ou serviço depois de ver o anúncio;
- **Approved conversion:** Número total de pessoas que compraram o produto depois de ver o anúncio.

# Perguntas a serem respondidas

1. Como saber o perfil do público alvo?
2. Qual são as campanhas que são mais Lucrativas?
3. Como podemos aumentar a Taxa de ROAS?

# Requisitos

- Python 3.5
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn
- Scipy