---
title: Quickstart - Set up automatic enrollment in Intune
description: Quickstart - Set up automatic enrollment for Windows 10 devices in Intune.
services: microsoft-intune
author: ErikjeMS

ms.service: microsoft-intune
ms.topic: quickstart
ms.date: 11/05/2018
ms.author: erikje
---

# Quickstart: Set up automatic enrollment for Windows 10 devices

In this quickstart, you'll set up Microsoft Intune to automatically enroll devices when specific users sign in to Windows 10 devices.

If you don’t have an Intune subscription, [sign up for a free trial account](free-trial-sign-up.md).

## Prerequisites

- Microsoft Intune subscription - [sign up for a free trial account](free-trial-sign-up.md).
- To complete this quickstart, you must first [create a user](quickstart-create-user.md) and [create a group](quickstart-create-group.md).

## Sign in to Intune

Sign in to the [Intune](https://aka.ms/intuneportal) as a Global Administrator or an Intune Service Administrator.

## Set up Windows 10 automatic enrollment

For this example, you'll use MDM enrollment so that both corporate and bring-your-own-devices can be automatically enrolled. You will sign up for a free Azure Active Directory Premium subscription.

1. In Azure, choose **Azure Active Directory** > **Mobility (MDM and MAM)**.
2. Select **Get a free Premium trial to use this feature**. Selecting this option will allow auto enrollment using the Azure Active Directory free Premium trial. 

    ![Select the Azure Active Directory free Premium trial](media/quickstart-setup-auto-enrollment/quickstart-setup-auto-enrollment-01.png)

    Choose the **Entrerprise Mobility + Security E5** free trial option. In addition, you must choose to **Activate** the free trial.

    ![Choose the Entrerprise Mobility + Security E5 free trial](media/quickstart-setup-auto-enrollment/quickstart-setup-auto-enrollment-02.png)

3. Select **Microsoft Intune**. 

    ![Choose Microsoft Intune from the list](media/quickstart-setup-auto-enrollment/quickstart-setup-auto-enrollment-03.png)

4. Select **Some** from the **MDM user scope** to use MDM auto-enrollment to manage enterprise data on your employees' Windows devices. MDM auto-enrollment will be configured for AAD joined devices and bring your own device scenarios.

    ![Select 'Some' from the Configure list](media/quickstart-setup-auto-enrollment/quickstart-setup-auto-enrollment-04.png)

5. Choose **Select groups** > **Contoso Testers** > **Select**.

    ![Select the group to enroll](media/quickstart-setup-auto-enrollment/quickstart-setup-auto-enrollment-05.png)

6. Use the default values for the remaining configuration values.
7. Choose **Save**.

## Clean up resources

To reconfigure Intune automatic enrollment, check out [Set up enrollment for Windows devices](windows-enroll.md).

## Next steps

In this quickstart, you learned how to set up auto-enrollment for Windows 10 devices. You can learn about other ways to enroll devices across all platforms. For more information about device enrollment, see [What is device enrollment?](device-enrollment.md)

> [!div class="nextstepaction"]
> [Quickstart: Enroll your Windows 10 device](quickstart-enroll-windows-device.md)