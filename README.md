# Análise de Dados Cardíacos

Este projeto consiste em uma análise exploratória de dados (AED) de um conjunto de dados relacionados a informações cardíacas. O objetivo é entender melhor os fatores que podem estar associados a um maior risco de ataque cardíaco.

## Descrição do Conjunto de Dados

O conjunto de dados utilizado neste projeto inclui as seguintes colunas:

- **Age:** Idade do paciente
- **Sex:** Gênero do paciente
- **exang:** Angina induzida por exercício
- **ca:** Número de vasos sanguíneos principais (0-3)
- **cp:** Tipo de dor no peito
- **trtbps:** Pressão arterial em repouso (mm Hg)
- **chol:** Colesterol em mg/dl
- **fbs:** Açúcar no sangue em jejum (1 = verdadeiro; 0 = falso)
- **rest_ecg:** Resultados eletrocardiográficos em repouso
- **thalach:** Frequência cardíaca máxima alcançada
- **target:** Alvo (0 = menos chance de ataque cardíaco; 1 = mais chance de ataque cardíaco)

## Objetivos da Análise

Os principais objetivos desta análise são:

1. Compreender a distribuição de características cardíacas no conjunto de dados.
2. Identificar possíveis correlações entre variáveis.
3. Visualizar tendências e padrões nos dados que possam ser relevantes para a previsão de ataques cardíacos.

## Estrutura do Projeto

- **Análise_Heart_Attack.ipynb:** Notebook Jupyter contendo a análise exploratória de dados.
- **heart.csv:** Conjunto de dados utilizado na análise.
- **LICENSE:** Licença para o projeto (opcional).

## Requisitos de Instalação

Para executar o notebook de análise, você precisará das seguintes bibliotecas Python:

- Pandas
- Matplotlib
- Seaborn

Você pode instalá-las usando o pip:

```shell
pip install pandas matplotlib seaborn
```

## Como Usar

1. Clone este repositório:

```shell
git clone https://github.com/opablodantas/Predicting-Heart-Attack-Risktg.git
```

2. Acesse o diretório do projeto:

```shell
cd Predicting-Heart-Attack-Risk
```

3. Execute o notebook Jupyter:

```shell
jupyter notebook Análise_Heart_Attack.ipynb
```

4. Siga as instruções no notebook para explorar os dados e visualizar os resultados.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) e enviar pull requests com melhorias ou correções.

## Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter detalhes.

---

**Autor:** Pablo Dantas
**Contato:** pablodantasevangelista@hotmail.com
```

Certifique-se de substituir os espaços reservados (como "Seu Nome", "seu@email.com", "https://github.com/seu-usuario/análise-de-dados-cardíacos.git" e outros) pelas informações reais do seu projeto. Esse README.md servirá como um guia para os usuários que visitarem o repositório no GitHub.
