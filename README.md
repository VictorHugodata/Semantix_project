# Segmentação de clientes (projeto encontrado no Kaggle)

Segmentação de clientes é a subdivisão de um mercado em grupos discretos de clientes que compartilham características semelhantes. A segmentação de clientes pode ser um meio poderoso para identificar necessidades insatisfeitas de clientes. Usando os dados acima, as empresas podem superar a concorrência desenvolvendo produtos e serviços exclusivamente atraentes.
Você é dono de um shopping de supermercado e, por meio de cartões de membro, tem alguns dados básicos sobre seus clientes, como ID do cliente, idade, sexo, renda anual e pontuação de gastos. Você quer entender os clientes como quem são os clientes-alvo para que o senso possa ser dado à equipe de marketing e planejar a estratégia adequadamente.

### Dicionário de dados

Os dados estão dispostos em uma tabela com uma linha para cada cliente, e uma coluna para cada variável armazenando as características desses indivíduos. Abaixo está o dicionário de dados com a explicação das variáveis no arquivo **segmentation data.csv**:

| Variável                | Descrição                                                                                                      | Tipo   |
| ----------------------- |:--------------------------------------------------------------------------------------------------------------:| -------|
| ID                      |  ID do cliente                                                                                                 | int64  |
| Sex                     |  Sexo do cliente(0 = homem, 1 = mulher)                                                                        | int64  |
| Martial status          |  Indica o estado civil do cliente (0=solteiro, 1=não solteiro(namorando, noivo, divorciado, viuvo))            | int64  |
| Age                     |  Indica a idade do cliente                                                                                     | int64  |
| Education               |  Índice qual é a escolaridade do cliente (0 = desconhecido/outra 1 = ensino medio, 2=graduado, 3=pós-graduado  | int64  |   
| Income                  |  Indica o salário do cliente por ano                                                                           | int64  |
| Occupation              |  Indica a ocupação do cliente (0=desempregado, 1=empregado, 2=alto-cargo                                       | int64  |
| Settlement size         |  Indica o tamanho da cidade que o cliente mora(0=pequena, 1=media, 2=grande )                                  | int64  |
