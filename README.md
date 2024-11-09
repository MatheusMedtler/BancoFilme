# BancoFilme

# Descrição:
## Armazenar dados do filme

# Estrutura do banco de dados: 
##  Tabela:
- Personagem
- Relacao 
- contexto_sociocultural
- tratamento 
- familia
- membrofamilia_tem

## Descrição; Armazenar as informações do usuario
## Colunas:
Tabela: Personagem 
- 'id_personagem' identificador unico do personagem
- fk_tratamento_id_tratamento Chave estrangeira de outra tabela chamada 'tratamento'
- fk_relecao_id_relacao Chave estrangeira de outra tabela chamada 'relacao'
- 'nome_personagem' Nome do personagem
- 'idade' Idade do personagem
- 'etnia_personagem' Diz o tom da melatonina do personagem
- 'personalidade' Descreve a personalidade do personagem
- 'profissão' Diz qualo trabalho do personagem
- 'conflito' Descreve os conflitos do personagem 
- 'genero' fala qual é o genero do personagem

Tabela : Relaçao
  
- 'id_relacao' Identificador unico da relacao
- 'tipo_de_relacao' Descreve qual o tipo da relacao

Tabela: Familia

- 'id_familia' Identificador unico da familia
- 'nome_familia' Nome da Familia
- 'descricao_familia' Descreve a descricao da familia

Tabela: Contexto_sociocultural
 
- 'id_contexto_sociocultural' Identificador unico do contexto socio cultural 
- 'fk_familia_id_familia' Chave estrangeira da familia
- 'fk_personagem_id_personagem' Chave estrangeira do personagem 
- 'lugar' Diz o local onde a familia/personagem moram
- 'classe_social' Diz a condicao da familia/personagem
- 'etnia_contexto_sociocultural'  Diz o tom da melatonina do personagem
- 'Cultura' Diz a cultura da familia/personagem

Tabela: Tratamento

- 'id_tratamento'  Identificador unico do tratamento
- 'descricao' Descreve o tratamento 
- 'nome_tratamento' Diz o nome do tratamento

  Tabela: Membrofamilia_tem

  - 'fk_personagem_id_personagem' Chave estrangeira do personagem 
  - 'fk_familia_id_familia' Chave estrangeira da familia
  - 'parentesco' Diz o parentesco de um personagem
  - 'funcao' Diz a funcao do personagem da familia
 
  # Diagrama ER

  ![texto] (url)
