# ai-youtube-summarizer-chrome-extension

You can run and test it in your Chrome browser by following these steps:

Open Chrome and navigate to the extensions management page by entering chrome://extensions/ in the address bar or by clicking on the menu button (three vertical dots in the top-right corner), then selecting "More tools" > "Extensions".

Enable "Developer mode" by toggling the switch in the top-right corner of the extensions page. This will enable additional options for loading and managing your unpacked extension.

Click the "Load unpacked" button that appears after enabling Developer mode. This will open a file dialog.

In the file dialog, navigate to the folder where your Yeoman-generated Chrome extension is located. Select the folder and click "Open" or "Select Folder" depending on your operating system.

Your extension should now be loaded and visible in the extensions management page. You should also see its icon in the Chrome toolbar, either as a Browser Action or Page Action, depending on the UI action you chose during the Yeoman setup.

Interact with your extension by clicking on its icon in the toolbar. If it's a Browser Action, it will show a popup, while a Page Action will only appear on specific web pages according to the rules you've defined in your extension.

As you develop your extension, you can make changes to the code in your text editor. To see the changes, return to the extensions management page (chrome://extensions/) and click the "Reload" button (circular arrow icon) below your extension. This will refresh the extension with your updates.

Remember to use Chrome Developer Tools for debugging and inspecting your extension's code. To access Developer Tools for the popup UI of a Browser Action, right-click the extension's icon in the toolbar and choose "Inspect popup". For a background script or content script, click on the "Inspect views" link or "Background page" link on the extension management page. This will open a separate Developer Tools window focused on the relevant part of your extension.