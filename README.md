# Strip-Windows-11

How to Debloat Windows 11 to Improve Performance
How to Debloat Windows 11 to Improve Performance
In our tutorial on how to speed up Windows 10, we recommended users to debloat Windows 10 to significantly improve the performance. In the same vein, we have come up with another detailed guide on how to debloat Windows 11 from resource-hogging services and apps. While Windows 11 has relatively less bloatware than Windows 10, every bit of optimization helps. Now, if you have an older PC and want a performance boost, learn how to debloat Windows 11 and keep Microsoft’s latest desktop OS lightweight and snappy.

Debloat Windows 11 From Unnecessary Apps and Services (2021)
Here, we are going to use Windows10Debloater, a popular script developed by Sycnex for debloating Windows 10. I tested this script on my Windows 11 computer running the stable build, and it worked successfully without any issue. The program was also able to remove a boatload of unnecessary packages that were eating up the resources.

Sure, the script has not added some Windows 11-centric changes like cleaning up the Start menu, removing stubs, etc., but these features should be added in the next update, hopefully. So, for now, let’s dive in and learn how to debloat Windows 11 from unnecessary junk.

Note: While the script is tried and tested, I would suggest you proceed with caution as it may break things. I have added caveats where to tread carefully in the steps below, so follow the process without fail. If you have an older computer and want to speed up Windows 11, this may help you a lot. But again, do it at your own risk.

1. First, press the Windows key once and type “powershell” in the Windows search bar. From the search results, click on the “Run as Administrator” option on the right pane.

Debloat Windows 11 From Unnecessary Apps and Services (2021)
2. Next, copy the below command and paste it into the PowerShell window. After that, hit Enter. It will automatically download the Windows 11 debloater script from the internet and launch the program within a few seconds. The command will also create a System Restore Point so you can easily move back to a working build in case anything goes wrong after performing any actions.

iwr -useb https://git.io/debloat|iex
Debloat Windows 11 From Unnecessary Apps and Services (2021)
3. After executing the command, Windows10Debloater will open up. Here, first off, I would suggest you click on “Disable Cortana” if you don’t use Microsoft’s voice assistant. This will take a second and completely remove the service from the background.

Debloat Windows 11 From Unnecessary Apps and Services (2021)
4. Next, go ahead and click on “Uninstall OneDrive” if you don’t use it on your Windows PC. Well, OneDrive will no longer pop up on startup, and you won’t see random backup prompts anymore.

Debloat Windows 11 From Unnecessary Apps and Services (2021)
5. After that, click on “Disable Telemetry/ Tasks“. This is an important step and will stop all kinds of background tracking services run by Microsoft. After this operation, you will find your PC’s resources have freed up considerably. Also, from a privacy perspective, you must perform this action to stop any kind of data harvesting.

disable windows 11 telemetry
6. Finally, coming to debloating Windows 11 from unnecessary apps and packages. I would not suggest you remove all bloatware at once as the list is configured for Windows 10. Instead, click on “Customize Blocklist“.

Debloat Windows 11 From Unnecessary Apps and Services (2021)
7. Here, go through the list and tick the apps and packages you want to remove.

For example, I found out the list was removing Microsoft Store, Microsoft Photos, Paint, Edge, Calculator, and other essential apps. So I unticked them. Similarly, if you don’t use your Windows PC for gaming, you can tick Xbox and other related services. Basically, if you are unsure about any package, keep it unchecked to be on the safe side. Finally, click the “Save custom….” at the bottom. Note that ticking an app will remove it and unticking will keep the app as it is.

customize blocklist
8. Now, click the “Remove Bloatware with Custom Blocklist” button. This process will take some time, so keep patience. After it’s done, restart your PC, and you will find that Windows 11 has been debloated.

Debloat Windows 11 From Unnecessary Apps and Services (2021)
9. Note that you might find Instagram, Facebook, etc. on the Start menu even after debloating. It’s because they are stubs to download a program and not an existing app on the system. In that case, you will have to right-click on the stubs and uninstall them right away. You can find more information from our guide on how to customize the Start menu on Windows 11. We have also compiled an article on how to remove items from the Recommended section in the Windows 11 Start Menu.

windows 11 without bloatware
Remove Bloatware and Stop Tracking Services on Windows 11
So that is how you can remove all kinds of junk that come pre-installed with Windows 11. Not just that, you can also disable all Telemetry services that take up a huge amount of resources in the background. Keep in mind, these services and apps are not temporarily offloaded but disabled through Registry. So in the future, it’s unlikely these services will start again automatically. Anyway, that is all from us. You can also check out the best Windows 11 settings to change after installation or steps to roll back to Windows 10 from Windows 11 from our linked articles. We hope this guide helped you speed up your Windows 11 PC or laptop. In case you have any questions, let us know in the comment section below.

TAGS Windows 11
46 Comments
