# Sumário executivo

![](https://img.shields.io/github/stars/wecchi/AdTracking-Fraud-Detection-Challenge) ![](https://img.shields.io/github/forks/wecchi/AdTracking-Fraud-Detection-Challenge) ![](https://img.shields.io/github/tag/wecchi/AdTracking-Fraud-Detection-Challenge) ![](https://img.shields.io/github/release/wecchi/AdTracking-Fraud-Detection-Challenge/explorer.r) ![](https://img.shields.io/github/issues/wecchi/AdTracking-Fraud-Detection-Challenge) ![](https://img.shields.io/bower/v/wecchi)

## Sobre

> O risco de fraude está em toda parte, especialmente para empresas que anunciam online, a fraude de cliques pode acontecer em um volume avassalador, resultando em dados de cliques enganosos e dinheiro desperdiçado. Os canais de anúncios podem aumentar os custos simplesmente clicando no anúncio em grande escala. Com mais de 1 bilhão de dispositivos móveis inteligentes em uso ativo todos os meses, a China é o maior mercado móvel do mundo e, portanto, sofre de grandes volumes de tráfego fradulento.

A [TalkingData](https://www.talkingdata.com/) é a maior plataforma independente de serviços de big data da China e cobre mais de 70% dos dispositivos móveis ativos em todo o país. Eles lidam com 3 bilhões de cliques por dia, dos quais 90% são potencialmente **fraudulentos**. Sua abordagem atual para evitar fraudes de cliques para desenvolvedores de aplicativos é medir a jornada do clique de um usuário em seu portfólio, e sinalizar endereços IP que produzem muitos cliques, mas nunca acabam instalando aplicativos. Com essas informações, eles construíram uma lista negra de IP e uma lista negra de dispositivos.

## Descrição
Prever se após o clique do anúncio o usuário fará o download para instalar o aplicativo.


## Dicionário de dados

As seguintes variáveis estão disponíveis para análise:

- ``ip``: endereço de clique.
- ``app``: id do aplicativo para marketing.
- ``device``:  identificação do tipo de dispositivo do telefone celular do usuário (por exemplo, iphone 6 plus, iphone 7, huawei mate 7, etc.)
- ``os``: versão do sistema operacional do celular do usuário
- ``channel``: id do canal do editor de anúncios móveis
- ``click_time``: data do clique com fuso horário (UTC)
- ``attributed_time``: hora do download do aplicativo quando o usuário baixar o aplicativo depois de clicar no anúncio
- ``is_attributed``: o alvo a ser previsto, indicando que o aplicativo foi baixado

[Origem dos dados: ``kaggle``](https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/data?select=train_sample.csv)
