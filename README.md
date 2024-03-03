# Dados Públicos e Grandes Eventos

Nesse projeto foi desenvolvido um Dashboard com o Looker Studio. Para isso, foram utilizados dados públicos oriundos dos chamados abertos na prefeitura do Rio de Janeiro.

## Painel Geral

O painel geral, tem informações gerais sobre os chamados abertos disponíveis, com informações como, por exemplo, o número total de chamados, o histórico de chamados abertos ao longo do tempo e quantos estão dentro do prazo de atendimento. Podendo filtrar também pelo tipo, subtipo e data.

<img src="/imagens/Painel.png">

## Painel de Grandes Eventos
No segundo painel, temos o foco nos grandes eventos ocorridos na cidade nos anos de 2022 e 2023. Nele temos um foco maior para os chamados de perturbação do sossego, mas também é possível filtrar por subtipo e tipo de outros chamados, além de poder selecionar o tipo de evento, ver dados sobre a localização dessas solicitações e médias diárias dos principais subtipos solicitados.

<img src="/imagens/Eventos.png">

Para o projeto, os dados foram conectados diretamente do BigQuery (plataforma de Data Warehouse da Google Cloud).

## Visualizando o Painel
A Dashboard pode ser vista [aqui](https://lookerstudio.google.com/s/uDBfSS4JgSI).

Para acessar a Dashboard, é necessário estar logado com a conta Google e ter acesso aos dados. O tutorial para acessar os dados está [aqui](https://docs.dados.rio/tutoriais/como-acessar-dados/#como-criar-uma-conta-na-gcp).

Caso não queira logar, pode ver o vídeo do funcionamento da Dashboard [aqui](https://drive.google.com/file/d/1yQrO9BoO38MzK80ZzXSU_EO25dJXulbq/view?usp=drive_link).
