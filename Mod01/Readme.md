# Lab 01: Building a web application on Azure platform as a service offerings

## Architecture:

![architecture_01](ZZ-lab/architecture_01.png)

**Resultado de la creación de los App Service Web y Api: **

![Captura](ZZ-lab/Captura.PNG)

![Captura2](ZZ-lab/Captura2.PNG)


![lab0102](ZZ-lab/lab0102.png)

**Connection String to storage account:**

```
DefaultEndpointsProtocol=https;AccountName=imgstorbmvb0101;AccountKey=9vLzgybKXZpaUYa2SJbVqNQFXa187qOYWXlj/sbzZ5a38TrfnRHlqtWKH5z2EyNtlHVTk8M/ry9WPVDLRnrYzw==;EndpointSuffix=core.windows.net
```

**URL WEB API:**

```
https://imgapibmvb01.azurewebsites.net
```

**Configuracion de la API Web**
![lab0100](ZZ-lab/lab0101.png)

**Configuración de la Web App**
![lab0101](ZZ-lab/lab0100.png)

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

