# ElasticSearch
Eshop Search Engine based on ElasticSearch

This jupyter notebook (elasticsearch.ipynb) shows how to create a search engine for an eshop by using ElasticSearch <br>
You can see the official documentation for ElasticSearch here https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html

The used dataset (data/df_products_details.pkl) has been created by scraping https://www.bestprice.gr/. You cand find details on the scraping procedure in my repository (scrape_bestprice) It contains 32.324 products <br><br>

<b>The logic</b>: <br>
A user gives a text query and a product category. So, the search engine searches for the products that belong to the specific category and their title is relevant to the query. 
