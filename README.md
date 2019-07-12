# dati.gov.it - lista dataset
la lista dei dataset presenti su dati.gov.it

La lista è stata ottenuta utilizzando la chiamata a questa API https://www.dati.gov.it/api/3/action/package_list per ottenere l'elenco di tutti i dataset pubblicati. Per ognuno degli oltre 25.000 dataset è stata fatta una chiamata a https://www.dati.gov.it/api/3/action/package_show?id="+id dove id è il nome del dataset di cui si vogliono le informazioni di dettaglio.

Per ogni dataset si ottengolo le seguenti informazioni:
name;title;revision_timestamp;metadata_created;metadata_modified;organization;date
dove date è la data in cui è stato effettuato lo scraping
