# Domoticanoelia
Resumo: 
Primero de todo preparamos un ordenador pequeño chamado noovi, para que fose a Nosa central domótica, instalamos e configuramos as aplicacions para ter o servidor mqtt preparado para conectar todos os sensores e actuadores que necesitemos

Cando xa instalamos o nosotros sistema operativo rp no noovi, procedimos a instalar mosquito e nodered e a partir de aquí o noso noovi xa estaría preparado para domotizar unha vivenda sendo o administrador e xestor de todos os datos que se manexen nesa rede.

Fixenos Unha proba de conexión desde o noso ordenador ao noovi, comprobando si funcionaba

Comenzamos coas prácticas en Arduino

Na práctica un, conectamos o esp32 a rede wifi e ao servidor mqtt
![EsquemaConexions_bb(2)](https://github.com/noeliaalvarezalvarez/Domoticanoelia/assets/171138946/ba33ce8c-c6ba-476a-baa8-cab59b570e42)

Na práctica dous, encendimos e apagamos un led, a través do panel de node red, pero antes tivemos que crear os fluxos en nodered
![flowP4noelia](https://github.com/noeliaalvarezalvarez/Domoticanoelia/assets/171138946/16fdeba4-bebf-487d-ac07-ea257c203ec0)


Na práctica tres, nesta práctica tamen acendimos un led, pero a través dun bonton que tamen configuramos a través de fluxos en node red
![nodos_noelia](https://github.com/noeliaalvarezalvarez/Domoticanoelia/assets/171138946/9e0f9da8-e137-429a-98da-4ce2b56ddf3b)

Na práctica 4 utilizamos tamen un sensor dht11 para medir a temperatura e humidade e facer funcionar un ventilador, accionado por un relé, está automatización a fixenos cos nodos de node red de tal
maneira que cando a temperatura ou a humidade pasen dun determinado valor o relé
activarase, facendo que o ventilador comece a funcionar.

![maqueta24](https://github.com/noeliaalvarezalvarez/Domoticanoelia/assets/171138946/916df20d-fed2-46d3-9b16-9031487ca4fd)






