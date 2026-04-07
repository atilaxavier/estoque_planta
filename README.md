#Estoque peixes sobre planta da piscicultura
Projeto para mostrar dados de estoque de peixes sobre planta da piscicultura.
Trata-se de webapp em javascript, que mostra sobre imagem SVG (.svg) pop-ups de texto com dados do estoque de peixes daquele tanque.
Dados do estoque são obtidos em planilhas disponiveis no Google Drive.
Arquivo .svg editado com o InkSpace, de modo a gerar identificadores de poligonos (retangulos) usaveis no javascript.
Conteudo do arquivo .svg (entre <svg...</svg>) é importado dentro do codigo javascript, para ser referenciado.
Mensalmente é necessário atualizar a URL do arquivo .csv disponibilizado pelo Google Drive a partir da planilha de estoque correspondente. Ex:       // Substitua pelo link CSV gerado no passo 1
      const csvUrl = 'https://docs.google.com/spreadsheets/d/e/2PACX-1vR_XRbnq_CbZ5NIZqVcCFaQGZrwBINe9-oHc7THPLDBD--SLs8AoSiYqZZMXGx1Zg/pub?gid=24569445&single=true&output=csv';

