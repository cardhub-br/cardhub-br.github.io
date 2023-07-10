

## Introdução

Essa guia apresenta o processo de conciliação de vendas que consiste na disponibilização em um servidor FTP um arquivo contendo o detalhamento de informações de vendas do dia anterior, com um tempo de permanência no servidor de 30 dias.

Para ativar essa funcionalidade, entre em contato com o time de implantação através dos canais de atendimento descritos na seção Introdução. O layout do arquivos segue o modelo apresentado nas tabelas abaixo:


## Registro de cabeçalho

|SEQ|CAMPO|CARA|CONTEÚDO|OBSERVAÇÕES|
|---|-----|----|--------|-----------|
|01|Identificação do Registro|Numérico|0|Identifica o registro Header|
|02|Enchimento|Texto|;||
|03|Código da Rede|Numérico|||
|04|Enchimento|Texto|;||
|05|Nome da Rede|Texto|||
|06|Enchimento|Texto|;||
|07|Enchimento|Texto|;||
|08|Data da Gravação|Numérico||Formato DDMMAAAA|
|09|Enchimento|Texto|;||
|10|Data do Movimento|Numérico||Formato DDMMAAAA|
|11|Enchimento|Texto|;||
|12|Quantidade<br/>Registros Transação|Numérico|||
|13|Enchimento|Texto|;||
|14|Valor Total Registros de Transação|Numérico|||
|15|Enchimento|Texto|;||
|16|Valor Total Comissão|Numérico|||
|17|Enchimento|Texto|;||
|18|Valor Total a Pagar|Numérico|||
|19|Enchimento|Texto|;||

