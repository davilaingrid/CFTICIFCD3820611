# Lab 07: Access resource secrets more securely across services 

## Escenario de laboratorio
Your company has a data-sharing business-to-business (B2B) agreement with another local business in which you're expected to parse a file that's dropped off nightly. To keep things simple, the second company has decided to drop the file as a Microsoft Azure Storage blob every night. You're now tasked with devising a way to access the file and generate a secure URL that any internal system can use to access the blob without exposing the file to the internet. You have decided to use Azure Key Vault to store the credentials for the storage account and Azure Functions to write the code necessary to access the file without storing credentials in plaintext or exposing the file to the internet.

## Objetivos
After you complete this lab, you will be able to:

Create an Azure key vault and store secrets in the key vault.

Create a server-assigned managed identity for an Azure App Service instance.

Create a Key Vault access policy for an Azure Active Directory identity or application.

Use the Storage .NET SDK to download a blob.


![Captura](ZZ-lab/Captura.PNG)

![Captura1](ZZ-lab/Captura1.PNG)

![Captura2](ZZ-lab/Captura2.PNG)

![Captura3](ZZ-lab/Captura3.PNG)

![Captura4](ZZ-lab/Captura4.PNG)

![Captura5](ZZ-lab/Captura5.PNG)

![Captura6](ZZ-lab/Captura6.PNG)

![Captura7](ZZ-lab/Captura7.PNG)

![Captura8](ZZ-lab/Captura8.PNG)

![Captura9](ZZ-lab/Captura9.PNG)

![Captura10](ZZ-lab/Captura10.PNG)

![Captura11](ZZ-lab/Captura11.PNG)

![Captura12](ZZ-lab/Captura12.PNG)

![Captura13](ZZ-lab/Captura13.PNG)

![Captura14](ZZ-lab/Captura14.PNG)

![Captura15](ZZ-lab/Captura15.PNG)

![Captura16](ZZ-lab/Captura16.PNG)

![Captura17](ZZ-lab/Captura17.PNG)

![Captura18](ZZ-lab/Captura18.PNG)

![Captura19](ZZ-lab/Captura19.PNG)

![Captura20](ZZ-lab/Captura20.PNG)

![Captura21](ZZ-lab/Captura21.PNG)

![Captura22](ZZ-lab/Captura22.PNG)

![Captura23](ZZ-lab/Captura23.PNG)

![Captura24](ZZ-lab/Captura24.PNG)

![Captura25](ZZ-lab/Captura25.PNG)

![Captura26](ZZ-lab/Captura26.PNG)

![Captura27](ZZ-lab/Captura27.PNG)

![Captura28](ZZ-lab/Captura28.PNG)

![Captura29](ZZ-lab/Captura29.PNG)

![Captura30](ZZ-lab/Captura30.PNG)

![Captura31](ZZ-lab/Captura31.PNG)

![Captura32](ZZ-lab/Captura32.PNG)

![Captura33](ZZ-lab/Captura33.PNG)

![Captura34](ZZ-lab/Captura34.PNG)

![Captura35](ZZ-lab/Captura35.PNG)

![Captura36](ZZ-lab/Captura36.PNG)

![Captura37](ZZ-lab/Captura37.PNG)

![Captura38](ZZ-lab/Captura38.PNG)

![Captura39](ZZ-lab/Captura39.PNG)

![Captura40](ZZ-lab/Captura40.PNG)

![Captura41](ZZ-lab/Captura41.PNG)

![Captura42](ZZ-lab/Captura42.PNG)

![Captura43](ZZ-lab/Captura43.PNG)

![Captura44](ZZ-lab/Captura44.PNG)

![Captura45](ZZ-lab/Captura45.PNG)

![Captura46](ZZ-lab/Captura46.PNG)

![Captura47](ZZ-lab/Captura47.PNG)

![Captura48](ZZ-lab/Captura48.PNG)

![Captura49](ZZ-lab/Captura49.PNG)

![Captura50](ZZ-lab/Captura50.PNG)

![Captura52](ZZ-lab/Captura52.PNG)

![Captura53](ZZ-lab/Captura53.PNG)
