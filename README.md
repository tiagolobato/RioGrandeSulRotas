# Rio Grande do Sul - Rotas e Estradas disponíveis
A situação do Rio Grande do Sul é alarmante e muitas estradas se encontram interditadas, bloqueadas ou com desvio. Esse projeto tem como objetivo facilitar a consulta, em tempo real, das rotas e estradas do Rio Grande do Sul, entre as cidades, e possíveis desvios causados pelas chuvas. Como estamos acompanhando, o Rio Grande do Sul tem enfrentado uma grande dificuldade com as chuvas e as enchentes. Muitas pessoas estão desabrigadas, e muitas estão transitando para outras cidades, buscando abrigo ou ajuda. Com as chuvas, muitas estradas foram interditadas ou destruídas, dificultando a movimentação das pessoas. Com essa aplicação, as pessoas vão poder consultar a melhor rota para transitarem de um lugar para outro e ficar cientes de possíveis problemas nas estradas.
A consulta das estradas é feita pelo site da Comando Rodoviário da Brigada Militar (CRBM): https://crbm.app.br/gestao-de-rotas/index.php?class=RotaCardList
   
## Resultados
Após perguntar qual a rota entre duas cidades o chat bot vai retornar a seguinte resposta

![image](https://github.com/tiagolobato/RioGrandeSulRotas/assets/53907497/ebe69df7-e226-424c-9383-02a5e6c857c7)

Ao clicar no link retornado podemos ver qual a rota sugerida no mapa:
![image](https://github.com/tiagolobato/RioGrandeSulRotas/assets/53907497/05a3ed76-189b-419e-9862-b3db2bd565d4)


## Execução do projeto

1. Para executar o projeto, basta fazer uma cópia do arquivo "Rotas.ipynb" e executá-lo no Colab (https://colab.research.google.com/).
2. Antes de executar os comandos no Colab, é preciso entrar no passo 'Configurar a API KEY' e alterar o valor "YOUR_API_KEY" para sua API Key do Gemini. 
![image](https://github.com/tiagolobato/RioGrandeSulRotas/assets/53907497/7390ee9c-f668-4ac7-b613-3541271eef0e)

3. Agora é só executar os blocos do notebook na ordem da página e, quando chegar no passo 'Generate text', executar e esperar o input para digitar sua pergunta aparecer.
![image](https://github.com/tiagolobato/RioGrandeSulRotas/assets/53907497/8cc41dbe-2665-46e3-bc2e-fdfe08604663)

4. Para finalizar o chat, é só digitar "sair".


