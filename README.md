# Scraping---Telelistas (Por / Eng)
https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white

Este é um projeto de web scraping do site www.telelistas.net. A pasta "tabelas", contém exemplos dos resultados que podem ser gerados. As tabelas não representam o resultado direto dos códigos aqui presentes. 

O projeto se divide em duas partes a serem explicadas a seguir: 

- O arquivo 'por_setor' coleta os as palavras-chave expostas em https://www.telelistas.net/rj/rio+de+janeiro. Para cada instância o código coleta também o numero de páginas a serem raspadas, e uma estimativa de lojas do setor.
- O arquivo 'bd--mongo' coleta diversos dados de cada loja. As palavras-chave são incialmente coletadas do arquivo 'setores.xlsx' gerado por 'por_setor', contudo os termos podem ser alterados conforme necessidade. Esse ajuste também pode ser feito ao ajustar o looping principal. Os dados também são salvos em um banco Mongo. Dados de senha foram omitidos, e 

