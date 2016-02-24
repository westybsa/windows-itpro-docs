---
Description: '.NET Framework problems with Internet Explorer 11'
MS-HAID: 'p\_ie11deploy.net\_framework\_problems\_with\_internet\_explorer\_11'
MSHAttr: 'PreferredLib:/library'
title: '.NET Framework problems with Internet Explorer 11'
---

# .NET Framework problems with Internet Explorer 11


If you’re having problems launching your legacy apps while running Internet Explorer 11, it’s most likely because Internet Explorer no longer starts apps that use managed browser hosting controls, like in the .NET Framework 1.1 and 2.0.

You can get IE11 to use managed browser hosting controls again, by:

![](../common/wedge.gif)**To turn managed browser hosting controls back on**

1.  **For x86 systems or for 32-bit processes on x64 systems:** Go to the HKLM/SOFTWARE/MICROSOFT/.NETFramework registry key and change the **EnableIEHosting** value to 1.

2.  **For x64 systems or for 64-bit processes on x64 systems:** Go to the HKLM/SOFTWARE/Wow6432Node/.NETFramework registry key and change the **EnableIEHosting** value to 1.

For more information, see the [Web Applications](http://go.microsoft.com/fwlink/?LinkId=308903) section of the Application Compatibility in the .NET Framework 4.5 page.

 

 


