# Merge - Feed + RSS

O _script_ `cepea_feed_rss_merge.ipynb` visa juntar as duas bases separadas:

* `AAAA-MM-DD cepea_feed_list.csv`
* `AAAA-MM-DD cepea_rss.csv`

Este processo deverá acontecer uma única vez, pois após este início o banco de dados será consolidado no arquivo:

* `AAAA-MM-DD cepea_feed_rss_merge.csv`

## TO-DOs

Posteriormente será necessário definir a rotina de atualização do arquivo `AAAA-MM-DD cepea_feed_rss_merge.csv`.