Hi,
I'm just right now going to explain the new feature which is spying (enumerating) menus of other applications. When you enumerate the parent windows you can right click any handle and if it has any menus the 'Spy Menus' option will be enabled otherwise disabled.

WARNING: If the parent having menus is MDI And its child windows are MAXIMIZED Then spying the menus wil CRASH EnumeratioonX and may also crash VB too if running inthe VB IDE, but if the child windows are not maximized then the menus will be spied accurately.

When the spy window is active and 'bring window to top' checkbox is checked then double clicking any menu item will bring the concerned window to top and show the actions of clicking the menu, however if the checkbox isnt checked then the EnumerationX will remain on top but the action of clicking will take place. It does not spy the menus of floating type toolbars like that of Word 97/2000, IE, but it can spy the menus of Adobe Acrobat, wordPAd , Calculator, Notepad, Winzip etc, the reason is that I dont seem to be getting the handle of the menus of IE or Word. whenever I can manage to do that I'll post an upgrade.

For questions and comments please feel free to contact me at <joehacker@yahoo.com> .  I hope this program helps you understand things you didnt know.
Regards.
 - Abubakar
