Conjunto de Dados de Avaliações de Filmes:

import pandas as pd

# Carregando o conjunto de dados de avaliações
df_ratings = pd.read_parquet

# Descrição do Conjunto de Dados de Avaliações
"""
Este conjunto de dados contém avaliações de usuários para filmes, extraídas do MovieLens.
Cada entrada inclui informações sobre o usuário, filme e a avaliação dada. 
Colunas Principais: 'user_id', 'item_id', 'rating', 'timestamp'.
"""

# Exibindo as últimas linhas do conjunto de dados
print(df_ratings.tail())

# Carregando o conjunto de dados de metadados de filmes
df_items = pd.read_parquet

# Descrição do Conjunto de Dados de Metadados de Filmes
"""
Este conjunto de dados fornece metadados detalhados sobre os filmes, como título e gênero.
Cada entrada corresponde a um filme, identificado por 'item_id'.
Colunas Principais: 'title', 'genres'.
"""

# Exibindo as últimas linhas do conjunto de dados
print(df_items.tail())


