## Descrição da Atividade

O Censo Escolar é o principal instrumento de coleta de informações da educação básica e a mais importante pesquisa estatística educacional brasileira, sendo realizado em colaboração entre o Inep, as secretarias estaduais e municipais de educação e com a participação de todas as escolas públicas e privadas do país. A partir dos dados obtidos pelo Censo Escolar, é possível compreender a situação educacional do país, das unidades federativas, dos municípios, bem como das escolas e, com isso, acompanhar a efetividade das políticas públicas. Você e sua equipe serão responsáveis por utilizar o framework de processamento distribuído PySpark para analisar os dados do Censo Escolar da Educação Básica coletados em 2021. Este conjunto de dados possui mais de 220 mil linhas e 370 colunas com dados coletados sobre todas as escolas brasileiras, conforme ilustrado abaixo.

![Screenshot_1](https://user-images.githubusercontent.com/90704921/202902096-a9b3b809-579d-425b-9481-f7564a7869eb.png)

O conjunto de dados “censo_escolar_2021.csv” está disponível no formato CSV. Nestearquivo, as colunas são separadas por ponto e vírgula (“;”). Devido ao grande número de colunas, também será fornecida uma planilha auxiliar chamada “descrição_colunas.xlsx”, que poderá ser utilizada para a compreensão do significado da informação armazenada em cada coluna, bem como a consulta do índice de uma determinada coluna de interesse. Por exemplo, o nome do munícipio das escolas é apresentado na coluna NO_MUNICIPIO (índice 6), conforme ilustrado na figura abaixo com a descrição das 10 primeiras colunas.

![Screenshot_2](https://user-images.githubusercontent.com/90704921/202902119-06e00b28-bc88-4444-a36e-526aadc66971.png)

## Orientação

Orientation: 
1. [ ] Não concluído
2. [x] Concluído

## Demandas

1. [] Número de escolas em Curitiba;
2. [] Número de escolas por Região Geográfica (NO_REGIAO) ordenado de acordo com o nome da região;
3. [] Nome (NO_ENTIDADE), município (NO_MUNICIPIO) e quantidade de docentes da escola que possui o maior número de professoressomando as categorias de Educação Básica (QT_DOC_BAS), Ensino Fundamental (QT_DOC_FUND) e Ensino Médio (QT_DOC_MED);
4. [] Quantidade média de matrículas de Ensino Médio (QT_MAT_MED) em relação ao total de escolas por Região Geográfica (NO_REGIAO);
5. [] Quantidade de escolas por Tipo da Localização (TP_LOCALIZACAO) e Tipo da Dependência Administrativa (TP_DEPENDENCIA);
6. [] Quantidade de escolas por Sigla da Unidade da Federação (SG_UF) e Tipo de Dependência Administrativa (TP_DEPENDENCIA), ordenada de acordo com as maiores quantidades.
