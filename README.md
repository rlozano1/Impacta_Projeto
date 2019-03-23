# Impacta_Projeto - Ult. Atualização em 23/03/2019

Este projeto contém dados de:

Últimos 14 anos: Quantidade de Contratos de Plano de Saúde Ativos/Inativos, Indice histórico da cotação do dólar, Indice histórico do IPCA, Saldo histórico do desemprego

Últimos 2 anos: Quantidade de Reclamações sobre Plano de Saúde registradas no site reclameaqui

Informaçōes e instruçōes de uso:

O uso de todo conteúdo deve ser feito exclusivamente pelo software de BI Qlik Sense Desktop. 
Link de Pré Requisitos para instalação: https://help.qlik.com/pt-BR/sense/November2018/Subsystems/Hub/Content/Sense_Hub/Introduction/install-desktop.htm

Link para download: https://da3hntz84uekx.cloudfront.net/QlikSenseDesktop/12.44/2/_MSI/Qlik_Sense_Desktop_setup.exe
(durante a instalação, marque a opção de uso das extension do tipo Bundle)

O arquivo do projeto que contempla os dados e dashboards (Impacta - Projeto Big Data Analytics.qvf), deve ser baixado na máquina local onde foi feita instalação da versão Desktop (gratuita) no mesmo diretório de instalação. Por padrão fica em: C:\Users\SEU_USUARIO\Documents\Qlik\Sense\Apps
Link para Download do arquivo do projeto: https://drive.google.com/drive/folders/1dq-WUWSrKayaE0DFtV2PPEriq1xqOakn?usp=sharing
Uma vez baixado e salvo na pasta indicada, basta abrir o Qlik Sense Desktop e abrir o aplicativo de acordo com o nome acima identificado.

Não é necessário fazer recarga dos dados, pois já estão compactados por completo dentro do arquivo .qvf baixado. De qualquer forma, como todo script de ETL esta incluso dentro do aplicativo, acessando o menu da camada "Dados", é possível modificar os caminhos de apontamento das "Libs" de configuração de origem destes dados. Deve-se apontar cada Lib de conexão ao diretório onde será baixado os dados brutos de origem de leitura.
Link para download dos dados brutos (somente se quiser fazer recarga para modificar algo na camada ETL, pois não se faz necessário): https://drive.google.com/drive/folders/1a4RSMz7ob-x0FCX6_TbhQ0D-je2UZRLB?usp=sharing

Dentro do aplicativo, nas pasta "Predição", existem objetos de uma extensão aberta do produto de nome "Advanced Analytcs Toolbox" que precisa ser baixada no computador local, assim como será necessário instalar o Software de Linguagem de programação chamado "R", qual contém as bibliotecas de analise Preditiva que estão sendo usadas neste projeto dentro do Qlik Sense. Todos os passos e arquivos necessários para instalação e configuração deste ambiente integrado estão descritos no arquivo "Installing R with Qlik Sense.pdf", onde neste caso deve-se seguir o passo a passo baseado na versão Desktop do Qlik Sense.
Link para download do .pdf de passo a passo: https://drive.google.com/file/d/19UED3JneBNkVvYTfvqVdDpYtRmaSmDfQ/view?usp=sharing
Link dos arquivos necessários para completar o passo a passo: https://drive.google.com/file/d/19Nrn4iCd-XrQ7ZeWwcnhi46gb3SA7xgw/view?usp=sharing
