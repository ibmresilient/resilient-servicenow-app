# How to install the update set on ServiceNow for v2.3.9
When upgrading using an update set the previously configured properties in of the app will be deleted. 

1. Log onto your ServiceNow instance through a web browser.
2. Click the tab named All.
3. Type System Update Sets.
4. From the list, select Retrieved Update Sets.
5. After the list of update sets under Related Links, click on Import Update Set from XML.
6. Click on the Browse button and select the XML update set.
7. Now click on the blue Upload button.
8. After it is uploaded, it will send you back to the previous page, where you will see a new row is added to the table with the name IBM Security QRadar SOAR.
9. In the data table under the name column, click on IBM Security QRadar SOAR.
10. On the new page that is opened in the top right corner, click on the white button that says Preview Update Set and wait for this process to finish.
11. When this fails, click on the white close button in the bottom left corner of the pop-up.
12. At the bottom left of the page, under the tab named Update Set Preview Problems, select the first empty check box to select all the update set preview problems.
13. Now in the bottom right corner of the page, click on the drop-down menu that says Actions on selected rows... and select the option Skip remote update.
14. Then in the top right corner, click the white button that says Commit Update Set.
15. A pop-up will open. Once this says Succeeded 100% click the white close button in the bottom right.
16. The app has now been installed successfully. The previously configured properties in of the app were removed.


# How to configure the properties for IBM Security QRadar SOAR app on ServiceNow
1. In the top left click the white All.
2. Now in the white box under All that says Filter type in IBM Security QRadar SOAR.
3. Under where it says IBM Security QRadar SOAR click on properties. A new tab will open in your browser.
4. In this new tab fill in the properties and when done click the blue Save button in the top right corner.
5. Close out that tab by clicking the X on the right side of the tab.
6. The properties are now configured and saved.


# How to test the connection of IBM Security QRadar SOAR app on ServiceNow
1. In the top left click the white All.
2. Now in the white box under All that says Filter type in IBM Security QRadar SOAR.
3. Under where it says IBM Security QRadar SOAR click on Test Connection. A new tab will open in your browser.
4. In the new tab click on the blue button that says Test Connection.
