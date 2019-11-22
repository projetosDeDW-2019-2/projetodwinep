# Projeto Data Warehouse INEP
Professora: Ceça Morais

Equipe: Blenda Guedes, Eduardo Uchôa, Juliana Ferreira e Murilo Dauro.

## Base de dados
Censo da Educação Superior 2015

Disponível em: http://inep.gov.br/microdados

## Arquivos
1. Modelo da base operacional: modeloOrigem.mwb

2. Script SQL de criação da base operacional com os inserts dos dados: dumpBaseOrigem.rar (Diponível em: https://drive.google.com/open?id=1dGtNcRlGPwhsPdJlnKZXq83cYDabFUTn)

3. Base operacional completa disponível online:  databases.000webhost.com

<b>Base Origem</b>

username: id11689118_admin1

senha: senha

<b>Base DW</b>

username: id11689118_admin

senha: senha

4. Modelo do DW: modeloDW.mwb

5. Script SQL de criação do DW vazio: dumpDWINEP.rar

6. Script SQL de criação do DW com os inserts dos dados: dumpDWINEP.rar

7. ETL Dimensões: ETL.rar

8. ETL Fatos: ETL.rar

9. Consultas OLAP: RespostasDW.rar (Subpastas com arquivos para cada questão), Respostas.pdf e Mapa de calor.pdf

10. Dicionário de dados: DicionarioDadosBaseOperacional.xls

11. Código da implementação dos mapas de calor: mapadecalor.R


## Mapa de Calor
Instalar RStudio em https://rstudio.com/products/rstudio/download/

Executar arquivo mapadecalor.R

Alterar arquivo csv conforme questão. (CSV e XLSX disponíveis na pasta de respostas)
