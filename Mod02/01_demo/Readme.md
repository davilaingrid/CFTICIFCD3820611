### Demo: Create an HTTP trigger function by using the Azure portal

In this demo, you'll learn how to use Functions to create a “hello world” function in the Azure portal. This demo has two main steps:

1. Create a Function app to host the function
2. Create and test the HTTP trigger function

To begin, sign in to the Azure portal at [https://portal.azure.com](https://portal.azure.com/) with your account.

#### Create a function app

You must have a function app to host the execution of your functions. A function app lets you group functions as a logic unit for easier management, deployment, and sharing of resources.

1. From the Azure portal menu, select **Create a resource**.

2. In the **New** page, select **Compute** > **Function App**.

3. Use the function app settings as specified in the table below.

   | Setting               | Suggested value      | Description                                                  |
   | --------------------- | -------------------- | ------------------------------------------------------------ |
   | **Subscription**      | Your subscription    | The subscription under which this new function app is created. |
   | **Resource Group**    | *myResourceGroup*    | Name for the new resource group in which to create your function app. |
   | **Function App name** | Globally unique name | Name that identifies your new function app. Valid characters are a-z (case insensitive), 0-9, and -. |
   | **Publish**           | Code                 | Option to publish code files or a Docker container.          |
   | **Runtime stack**     | Preferred language   | Choose a runtime that supports your favorite function programming language. Choose **.NET** for C# and F# functions. |
   | **Region**            | Preferred region     | Choose a region near you or near other services your functions access. |

4. Select the **Next : Hosting >** button and enter the following settings for hosting.

   | Setting              | Suggested value            | Description                                                  |
   | -------------------- | -------------------------- | ------------------------------------------------------------ |
   | **Storage account**  | Globally unique name       | Create a storage account used by your function app. You can accept the account name generated for you, or create one with a different name. |
   | **Operating system** | Preferred operating system | An operating system is pre-selected for you based on your runtime stack selection, but you can change the setting if necessary. |
   | **Plan**             | Consumption plan           | Hosting plan that defines how resources are allocated to your function app. In the default **Consumption Plan**, resources are added dynamically as required by your functions. |

   

5. Select **Review + Create** to review the app configuration    ![Captura](images/Captura.PNG)
selections.

![Captura1](images/Captura1.PNG)

![Captura2](images/Captura2.PNG)


6. Select **Create** to provision and deploy the function app. When the deployment is complete select **Go to resource** to view your new function app.

Next, you'll create a function in the new function app.

#### Create and test the HTTP triggered function

1. Expand your new function app, then select the **+** button next to **Functions**.

![Captura3](images/Captura3.PNG)

![Captura4](images/Captura4.PNG)

![Captura5](images/Captura5.PNG)


2. Select the **In-portal** development environment, and select **Continue**.

3. Choose **HttpTrigger1** and then select **Create**.

A function is created using a language-specific template for an HTTP triggered function.![demo0203](demo0203.png)

##### Test the function

![Captura6](images/Captura6.PNG)

![Captura7](images/Captura7.PNG)

![Captura8](images/Captura8.PNG)

![Captura8.1](images/Captura8.1.PNG)

![Captura9](images/Captura9.PNG)

![Captura10](images/Captura10.PNG)

![Captura11](images/Captura11.PNG)

![Captura12](images/Captura12.PNG)



1. In your new function, click **</> Get function URL** at the top right.

2. In the dialog box that appears select **default (Function key)**, and then click **Copy**.

3. Paste the function URL into your browser's address bar. Add the query string value &name=<yourname> to the end of this URL and press the Enter key on your keyboard to execute the request. You should see the response returned by the function displayed in the browser.

4. When your function runs, trace information is written to the logs. To see the trace output from the previous execution, return to your function in the portal and click the arrow at the bottom of the screen to expand the **Logs**.

#### Clean up resources

You can clean up the resources created in this demo simply by deleting the resource group that was created early in the demo.

![Captura13](images/Captura13.PNG)

![Captura14](images/Captura14.PNG)

![Captura15](images/Captura15.PNG)

![Captura16](images/Captura16.PNG)

![Captura17](images/Captura17.PNG)

![Captura18](images/Captura18.PNG)

![Captura19](images/Captura19.PNG)

![Captura20](images/Captura20.PNG)

![Captura21](images/Captura21.PNG)

![Captura22](images/Captura22.PNG)

![Captura23](images/Captura23.PNG)
