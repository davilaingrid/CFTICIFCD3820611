# Lab 01: Building a web application on Azure platform as a service offerings

## Architecture:

![architecture_01](ZZ-lab/architecture_01.png)

**Resultado de la creación de los App Service Web y Api: **

Creando una Storage account

![Captura](ZZ-lab/Captura.PNG)


Creando una Web App imgapidavilaingrid

![Captura](ZZ-lab/Captura1.PNG)


![Captura2](ZZ-lab/Captura2.PNG)


Creando una Web App imgwebdavilaingrid

![Captura2](ZZ-lab/Captura3.PNG)



**Configuracion de la API Web**
![Captura4](ZZ-lab/Captura4.PNG)



**Configuración de la Web App**
![Captura5](ZZ-lab/Captura5.PNG)

**Código Az-CLI para desplegar el api rest**

```
az webapp deployment source config-zip --resource-group ManagedPlatform --src api.zip --name imgapibmvb01
```

**Código Az-CLI para desplegar el web app**

``` 
az webapp deployment source config-zip --resource-group ManagedPlatform --src web.zip --name imgwebbmvb0101
```


**Comprobación que las web api funcione correctamente **
![lab0105](ZZ-lab/lab0105.png)

**Comprobación que la web app funcione correctamente **
![lab0104](ZZ-lab/lab0104.png)

