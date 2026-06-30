# Projeto: Analise do Preco de Combust?iveis (2013-2026)

Este repositorio contem os scripts em R, as bases de dados e o relatorio gerado referentes ao trabalho final da disciplina de EST 100 - Estatastica Descritiva e Exploratoria da Universidade Federal de Vi??osa (UFV).

##  Equipe
* Diogo
* L??via
* Gabriel Resende

## Estrutura de Diretorios
Para que o codigo funcione corretamente e reproduza a nossa analise, o projeto exige a seguinte estrutura de pastas:

```text
meu_projeto/
????????? codigos/
???   ????????? analise_precos.Rmd        <- Script principal com a analise
????????? dados/
???   ????????? brutos/
???   ???   ????????? preco_regioes_bruto.csv <- Dados da ANP
???   ???   ????????? ipca_bruto.csv          <- Dados do IBGE
???   ????????? tratados/                 <- (Ser?? criada automaticamente pelo script)
????????? README.md
```
Pre-requisitos
Certifique-se de ter o R e o RStudio instalados. Antes de rodar, instale as bibliotecas necessarias executando o seguinte comando no seu console do R:
install.packages(c("tidyverse", "janitor", "dplyr", "tidyr", "stringr", "lubridate", "ggplot2", "gridExtra"))
Como Reproduzir a An??lise
Faca o download ou clone esta pasta para o seu computador.

Abra o arquivo analise_precos.Rmd no RStudio.

Nao e necessario criar pastas manualmente ou alterar diretorios. O c?odigo possui um comando dir.create() que gerencia isso de forma automatica.

Clique no botao Knit (na barra superior do RStudio) para compilar o codigo.

O RStudio ira executar todo o tratamento de dados, salvar as versoes tratadas em .csv na pasta dados/tratados/ e gerar o relatorio final em PDF/HTM