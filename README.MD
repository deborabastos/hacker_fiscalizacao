# Processo seletivo para a vaga de Hacker de Fiscalização e Análise de Dados do Gabinete Compartilhado

### Canditada: Débora Alves Pereira Bastos (CPF: 009.129.431-22)

### Problema:
Crie um arquivo notebook contendo o código (preferencialmente em Python e com comentários) e uma discussão em texto que respondam ao enunciado abaixo.

"Baseado na tabela em CSV com a série histórica 'Remuneração líquida média mensal no Executivo civil federal ativo, por sexo e raça (1999-2020)', disponível no site do Atlas do Estado Brasileiro (IPEA), comente uma ou duas tendências da evolução da remuneração destes servidores de acordo com seu sexo e/ou raça."

O texto de discussão completo pode ser visualizado [aqui](https://github.com/deborabastos/hacker_fiscalizacao/blob/main/debora_bastos_hacker_fiscalizaca_congresso_nacional.pdf).

A seguir, destaco os principais achados da análise:

![Alt text](https://github.com/deborabastos/hacker_fiscalizacao/blob/main/output/grafico1.png)

- em todos os anos, homens brancos apresentaram salário médio maior que as demais categorias, seguido por mulheres brancas, homens negros e, por último, mulheres negras;

- todas as categorias de servidores públicos civis federais ativos tiveram aumento real em seu salarial médio entre 1999 e 2020;

- o salário médio de todas as categorias se comportou de maneira similar, isto é, certa estabilidade entre 1999 e 2006, crescimento entre 2006 e 2011, e nova estabilidade entre 2011 e 2020;

- o salário médio da mulher negra, em nenhum dos 21 anos pesquisados, chegou ao valor percebido, em média, pelo homem branco de 1999;

- a categoria homem negro apenas em 2014 e 2017 atingiu o patamar salarial do homem branco de 1999;

- a mulher branca apenas alcançou o salário do homem branco de 1999 em 2009, ou seja, 10 anos após o salário índice considerado;

- a disparidade salarial caiu, ainda que lentamente, para mulheres brancas e mulheres negras. Para homens negros, ela aumentou.


<details>
<summary><ins>Notas de reprodutibilidade</ins></summary>
<p><ins>Para reproduzir corretamente o projeto, é necessário instalar os requisitos disponíveis no arquivo requirements.txt</ins></p>
```
pip install -r requirements.txt
```
</details>
