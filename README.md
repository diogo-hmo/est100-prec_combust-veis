# Projeto: An??lise do Pre??o de Combust??veis (2013-2026)

Este reposit??rio cont??m os scripts em R, as bases de dados e o relat??rio gerado referentes ao trabalho final da disciplina de **EST 100 - Estat??stica Descritiva e Explorat??ria** da Universidade Federal de Vi??osa (UFV).

## ???? Equipe
* Diogo
* L??via
* Gabriel Resende

## ???? Estrutura de Diret??rios
Para que o c??digo funcione corretamente e reproduza a nossa an??lise, o projeto exige a seguinte estrutura de pastas:

```text
meu_projeto/
????????? codigos/
???   ????????? analise_precos.Rmd        <- Script principal com a an??lise
????????? dados/
???   ????????? brutos/
???   ???   ????????? preco_regioes_bruto.csv <- Dados da ANP
???   ???   ????????? ipca_bruto.csv          <- Dados do IBGE
???   ????????? tratados/                 <- (Ser?? criada automaticamente pelo script)
????????? README.md
```
Pr??-requisitos
Certifique-se de ter o R e o RStudio instalados. Antes de rodar, instale as bibliotecas necess??rias executando o seguinte comando no seu console do R:
install.packages(c("tidyverse", "janitor", "dplyr", "tidyr", "stringr", "lubridate", "ggplot2", "gridExtra"))
Como Reproduzir a An??lise
Fa??a o download ou clone esta pasta para o seu computador.

Abra o arquivo analise_precos.Rmd no RStudio.

N??o ?? necess??rio criar pastas manualmente ou alterar diret??rios. O c??digo possui um comando dir.create() que gerencia isso de forma autom??tica.

Clique no bot??o Knit (na barra superior do RStudio) para compilar o c??digo.

O RStudio ir?? executar todo o tratamento de dados, salvar as vers??es tratadas em .csv na pasta dados/tratados/ e gerar o relat??rio final em PDF/HTM