---
author: wolfma61
ms.service: cognitive-services
ms.topic: include
ms.date: 07/05/2019
ms.author: wolfma
---

1. Open Visual Studio 2019.

1. In the Start window, select **Create a new project**. 

1. Select **Console App (.NET Framework)**, and then select **Next**.

1. In **Project name**, enter `helloworld`, and then select **Create**.

1. From the menu bar in Visual Studio, select **Tools** > **Get Tools and Features**, and check whether the **.NET desktop development** workload is available. If the workload hasn't been installed, mark the checkbox, then select **Modify** to start the installation. It may take a few minutes to download and install.

   If the checkbox next to **.NET desktop development** is selected, you can close the dialog box now.

   ![Enable .NET desktop development](../articles/cognitive-services/speech-service/media/sdk/vs-enable-net-desktop-workload.png)

The next step is to install the [Speech SDK NuGet package](https://aka.ms/csspeech/nuget), so you can reference it in the code.

1. In the Solution Explorer, right-click `helloworld`, and then select **Manage NuGet Packages** to show the NuGet Package Manager.

   ![NuGet Package Manager](../articles/cognitive-services/speech-service/media/sdk/vs-nuget-package-manager.png)

1. In the upper-right corner, find the **Package Source** drop-down box, and make sure that **nuget.org** is selected.

1. In the upper-left corner, select **Browse**.

1. In the search box, type `Microsoft.CognitiveServices.Speech` package and press Enter.

1. Select `Microsoft.CognitiveServices.Speech`, and then select **Install** to install the latest stable version.

   ![Install Microsoft.CognitiveServices.Speech NuGet package](../articles/cognitive-services/speech-service/media/sdk/qs-csharp-dotnet-windows-03-nuget-install-1.0.0.png)

1. Accept all agreements and licenses to start the installation.

   After the package is installed, a confirmation appears in the **Package Manager Console** window.

Now, to build and run the console application, create a platform configuration matching your computer's architecture.

1. From the menu bar, select **Build** > **Configuration Manager**. The **Configuration Manager** dialog box appears.

   ![Configuration Manager dialog box](../articles/cognitive-services/speech-service/media/sdk/vs-configuration-manager-dialog-box.png)

1. In the **Active solution platform** drop-down box, select **New**. The **New Solution Platform** dialog box appears.

1. In the **Type or select the new platform** drop-down box:
   - If you're running 64-bit Windows, select **x64**.
   - If you're running 32-bit Windows, select **x86**.

1. Select **OK** and then **Close**.
