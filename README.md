# Impacta_Projeto

Informaçōes e instruçōes de uso:

O uso de todo conteúdo deve ser feito exclusivamente pelo software de BI Qlik Sense Desktop.

Link para download: https://da3hntz84uekx.cloudfront.net/QlikSenseDesktop/12.44/2/_MSI/Qlik_Sense_Desktop_setup.exe
(durante a instalação, marque a opção de uso das extension do tipo Bundle)

O arquivo do projeto que contempla os dados e dashboards (Impacta - Projeto Big Data Analytics.qvf), deve ser baixado na máquina local onde foi feita instalação da versão Desktop (gratuita) no mesmo diretório de instalação. Por padrão fica em: C:\Users\SEU_USUARIO\Documents\Qlik\Sense\Apps

Download do arquivo do projeto: https://drive.google.com/drive/folders/1dq-WUWSrKayaE0DFtV2PPEriq1xqOakn?usp=sharing

Caso seja necessário recarregar os dados, estes estão armazenados em diretório público do Google Drive: 
https://drive.google.com/drive/folders/1a4RSMz7ob-x0FCX6_TbhQ0D-je2UZRLB?usp=sharing

Para recarregar os dados, basta criar sua própria Lib de conexão que aponte ao diretório onde baixou os dados de leitura e modificar o caminho da Lib original apontada para cada arquivo de origem ou grupo de arquivos de origem na camada de script (load) do Qlik Sense.
