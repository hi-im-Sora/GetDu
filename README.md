# GetDu
Pacote para trabalhar facilmente com dias úteis.

Função principal "get_du" retorna uma data frame com as variáveis de data do mês atual, e do mesmo dia útil do mês anterior, já considerando feriados.

Para instalar basta extrair o arquivo zipado, e rodar o seguinte código dentro do R.

##install.packages(devtools) ##Descomentar caso não tenha o pacote devtools instalado.

library(devtools)

setwd(folder_directory)

install(getDu)
