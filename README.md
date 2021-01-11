# wirds-2021-binder-example

Files we need to corerect execute binder:

1. 'runtime.txt' -- określamy z jakiej wersji R będziemy korzystać oraz z jakiego dnia mają być pakiety (np. r-'2021-01-01', '2021-01-01'

binder link:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zyechu/wirds-2021-binder-example.git/main?urlpath=rstudio)

Możemy założyc jakie pakity mają być w ramach tego obrazu w takim razie ppowinniśmy utworzyć plk o nazwie 'install.R', który będzie zawierał skrpy do instalacji ipakietów na przykłąd:

"""r
install.packages("tidyverse")
install.packages("data.tabel")
install.packages("sf")
install.packages("rio")
'''
