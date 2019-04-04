# <a name="completed-module-add-azure-ad-authentication"></a><span data-ttu-id="5695f-101">Módulo completado: agregar autenticación de Azure AD</span><span class="sxs-lookup"><span data-stu-id="5695f-101">Completed module: Add Azure AD authentication</span></span>

<span data-ttu-id="5695f-102">La versión del proyecto en este directorio refleja cómo completar el tutorial hasta [Agregar autenticación de Azure ad](https://docs.microsoft.com/graph/training/angular-tutorial?tutorial-step=3).</span><span class="sxs-lookup"><span data-stu-id="5695f-102">The version of the project in this directory reflects completing the tutorial up through [Add Azure AD authentication](https://docs.microsoft.com/graph/training/angular-tutorial?tutorial-step=3).</span></span> <span data-ttu-id="5695f-103">Si usa esta versión del proyecto, deberá completar el resto del tutorial a partir de [obtener datos de calendario](https://docs.microsoft.com/graph/training/angular-tutorial?tutorial-step=4).</span><span class="sxs-lookup"><span data-stu-id="5695f-103">If you use this version of the project, you need to complete the rest of the tutorial starting at [Get calendar data](https://docs.microsoft.com/graph/training/angular-tutorial?tutorial-step=4).</span></span>

> <span data-ttu-id="5695f-104">**Nota:** Se supone que ya ha registrado una aplicación en el portal de registro de aplicaciones, como se especifica en [registrar la aplicación en el portal](https://docs.microsoft.com/graph/training/angular-tutorial?tutorial-step=2).</span><span class="sxs-lookup"><span data-stu-id="5695f-104">**Note:** It is assumed that you have already registered an application in the app registration portal as specified in [Register the app in the portal](https://docs.microsoft.com/graph/training/angular-tutorial?tutorial-step=2).</span></span> <span data-ttu-id="5695f-105">Debe configurar esta versión del ejemplo de la siguiente manera:</span><span class="sxs-lookup"><span data-stu-id="5695f-105">You need to configure this version of the sample as follows:</span></span>
>
> 1. <span data-ttu-id="5695f-106">Cambie el nombre `oauth.ts.example` del archivo `oauth.ts`a.</span><span class="sxs-lookup"><span data-stu-id="5695f-106">Rename the `oauth.ts.example` file to `oauth.ts`.</span></span>
> 1. <span data-ttu-id="5695f-107">Edite `oauth.ts` el archivo y realice los cambios siguientes.</span><span class="sxs-lookup"><span data-stu-id="5695f-107">Edit the `oauth.ts` file and make the following changes.</span></span>
>     1. <span data-ttu-id="5695f-108">Reemplace `YOUR_APP_ID_HERE` por el **identificador de aplicación** que obtuvo desde el portal de registro de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="5695f-108">Replace `YOUR_APP_ID_HERE` with the **Application Id** you got from the App Registration Portal.</span></span>