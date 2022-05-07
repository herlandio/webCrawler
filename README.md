# Web Crawler para extração de dados da pagina [www.gov.br/compras](https://www.gov.br/compras/pt-br/acesso-a-informacao/noticias)

- Clone o projeto

  `git clone https://github.com/herlandio/webCrawler`
  
- Instale as dependências utilizando

  `composer install`
  
- No arquivo src/crawler.php basta definir de quantas paginas serão extraidas as informações

  `(new WebCrawler())->getPages(5);`
  
- Para executar o script acesse src/crawler.php e execute em linha de comando CMD ou Terminal

  `php crawler.php`
  
- Após a execução do script ira gerar uma planilha excel com todas as informações exportadas, a planilha estará na pasta src
