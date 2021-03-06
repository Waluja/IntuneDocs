---
title: Quickstart - Enroll your Windows 10 Desktop device in Microsoft Intune
description: Quickstart - Use the Company Portal to enroll your Windows 10 Desktop device into Microsoft Intune.
services: microsoft-intune
author: ErikRe
ms.author: erikre
manager: dougeby
ms.date: 11/06/2018
ms.topic: quickstart
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 658a7655-a6df-4dbe-b56c-22c7fc60e706
---

# Quickstart: Enroll your Windows 10 device

In this quickstart, you'll first take the role of an Intune user and enroll your Windows 10 device into Microsoft Intune. Then, you return to Intune and confirm the enrolled device.

Enrolling your devices into Microsoft Intune allows your Windows 10 devices to get access to your organization’s secure data, including email, files, and other resources. This is true for both Windows 10 desktop and Windows 10 Mobile devices. Enrolling your devices helps secure this access for both you and your organization, and helps keep your work data separate from your personal data.

> [!TIP]
> Find out what happens when you [enroll your device in Intune](/intune-user-help/what-happens-if-you-install-the-company-portal-app-and-enroll-your-device-in-intune-windows.md) and what that means for the [information on your device](/intune-user-help/what-info-can-your-company-see-when-you-enroll-your-device-in-intune.md).

If you don’t have an Intune subscription, [sign up for a free trial account](free-trial-sign-up.md).

## Prerequisites

- Microsoft Intune subscription - [sign up for a free trial account](free-trial-sign-up.md)
- To complete this quickstart, you must complete the steps to [setup automatic enrollment in Intune](quickstart-setup-auto-enrollment.md).

## Confirm your Windows 10 Desktop version

Before enrolling your Windows 10 Desktop, you must confirm the version of Windows that you have installed.

1. Right-click the Windows **Start** icon and select **Settings** to display Windows Settings options.

   ![Screenshot of Windows Settings - System](media/quickstart-enroll-windows-device/quickstart-enroll-windows-device-01.png)

2. Select **System** > **About**. 

   ![Screenshot of your system settings](media/quickstart-enroll-windows-device/quickstart-enroll-windows-device-02.png)

    > [!TIP]
    > You can also type the phrase "About your PC" into the **search bar**, then select **About your PC**.

3. In the **Settings** window you will see a list of **Windows specifications** for your PC. Within this list, locate the **Version**.

4. Confirm that the Windows 10 **Version** is **1607 or higher**.

    > [!IMPORTANT]
    > The steps presented in this quickstart are for Windows 10 version **1607 or higher**, if your version is **1511 or less**, continue with [these steps](/intune-user-help/enroll-your-w10-device-your-account.md).

## Enroll Windows 10 Desktop

1. Return to Windows Settings and select **Accounts**.

   ![Screenshot of your system settings - Accounts](media/quickstart-enroll-windows-device/quickstart-enroll-windows-device-03.png)

2. Select **Access work or school** > **Connect**.

    ![Select Access work school account](media/quickstart-enroll-windows-device/quickstart-enroll-windows-device-04.png)

3. Sign in to Intune with your work or school account, and then select **Next**. If you followed the [create a user and assign a license] quickstart, you can sign in with the user account that you created.

    > [!NOTE]
    > If you setting up an ".onmicrosoft.com", the user account will have **.onmicrosoft.com** as part of the account address. 

   ![Enter your work or school account](media/quickstart-enroll-windows-device/quickstart-enroll-windows-device-05.png)

    You’ll see a message indicating that your company or school is registering your device.

4. When you see the **You’re all set!** screen, select **Done**. You’re done.

5. You will now see the added account as part of the **Access work or school** settings on your Windows Desktop.

   ![Screenshot of newly added account](media/quickstart-enroll-windows-device/quickstart-enroll-windows-device-06.png)

    If you followed the previous steps, but still can’t access your work or school email account and files, follow the steps in [Troubleshooting steps to follow if you see Access work or school](/intune-user-help/troubleshoot-your-windows-10-device-windows.md#troubleshooting-steps-to-follow-if-you-see-access-work-or-school).

## Confirm your device enrollment in Intune

1. Sign in to [Intune](https://aka.ms/intuneportal) as a Global Administrator or an Intune Service Administrator.
2. Select **Devices** to view the enrolled devices in Intune.
3. Verify that you have an additional device enrolled within Intune.

   ![Screenshot Intune enrolled devices](media/quickstart-enroll-windows-device/quickstart-enroll-windows-device-07.png)

## Clean up resources

To unenroll your Windows device, see [Remove your Windows device from management](/intune-user-help/unenroll-your-device-from-intune-windows.md).

## Next steps

In this quickstart, you learned how to enroll a Windows 10 device into Intune. You can learn about other ways to enroll devices across all platforms. For more information about device enrollment, see [What is device enrollment?](device-enrollment.md)

> [!div class="nextstepaction"]
> [Quickstart: Set a required password length for Android devices](quickstart-set-password-length-android.md)