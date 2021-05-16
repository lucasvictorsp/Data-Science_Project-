### Tratamento dos dados, Predição, Classificação e Clusterização

<font style="font-family: monaco">DadosDeliciousFood.csv</font>
Este documento descreve o trabalho realizado na base de dados <font style="font-family: monaco">DadosDeliciousFood.csv</font> (*DDF*). Esta base de dados pertence a uma empresa *fictícia* do ramo alimentício, e para facilitar algumas explicações ela será nomeada como *Delicious Food* (*DF*). A DF tem suas operações consolidadas na cidade do *Rio de Janeiro* e pretende expandir-se para a cidade de *São Paulo*. Dada a relevância do problema apresentado, este trabalho tem o objetivo de estudar a DDF para extrair informações que ajudem a DF a tomar a decisão mais **assertiva possível**.<br/>
<br/> 
A DDF é uma matriz bidimensional (*2D*) de tamanho 456x24, onde cada linha representa um bairro. Como a DF possui operações somente na cidade do Rio de Janeiro, as informações privadas, isto é, que advém do banco de dados da DF, só estão disponíveis para bairros do Rio de Janeiro. Note que todo o trabalho está concentrado exatamente em conseguir definir valores confiáveis para esses campos nos bairros da cidade de São Paulo. Em posse desses valores a DF terá uma segurança maior para tomar a decisão se deve ou não expandir suas operações.<br/>
<br/>
Este trabalho em 4 seções, são elas:<br/> 
- **Tratamento dos Dados:** onde é feita a limpeza dos dados e uma análise das características (variáveis) dos bairros. 
- **Predição:** onde é feita a predição de alguns valores faltantes com relação aos bairros de São Paulo; 
- **Classificação:** nesta parte os bairros de São Paulo são classificados de acordo com seu potencial (baixo, médio e alto) de investimento que eles têm para a DF; 
- **Clusterização:** o último tópico visa agrupar os bairros com relação a proximidade dos dados.
<br/>
O arquivo [Relatório](https://github.com/lucasvictorsp/Data-Science_Project_DF/blob/main/doc/Relat%C3%B3rio%20T%C3%A9cnico.pdf) contém a descrição da análise de forma detalhada.