# Nexa-Proxima
BTP SAP MDK (Mobile Development Kit)


Bring up story board 

in command pallette - type ">" then type "storyboard"

best way to test the app functionality with preview is to push the changes (deploy) to the app and view the app in mobile or ssam app device.


[Referred here for data table option](https://help.sap.com/doc/3642933ef2e1478fb1578ef2acba4ae9/Latest/en-US/reference/schemadoc/Page/SectionedTable/Container/DataTable.schema.html)


</br> 

#### Applications - [code samples 0](https://github.com/SAP-samples/cloud-mdk-tutorial-samples) || [code samples 1](https://github.com/SAP-samples/cloud-mdk-samples/tree/main/Showcase_Apps)

- FormCell Inline Validation
- Home Screen Widget
- Image Handling
- Multi-Select & Context Menu
- PDF Generation
- Persistent Filters
- Printing and QR Codes
- Extension Samples
- Calender View
- Video Player
- NativeScript View

</br> </br>


### Common problems in MDK - development and deployment - git push and git pull

- DEPLOYMENT - during deployment when right click - MDK deploy is pressed it should as deploy as mobile / cloud foundry app / etc choose [Mobile] and next option mobile service standard / ne0 / etc [standard] next option should be whic hbuild want deploy here usually it should ask, but if it doesnt ask - DELETE "Project.json" file this could cause issue you may deploy to wrong MDK build if it was not chosen 
 
- BEST PRACISE - always pull from the MASTER or MAIN version then make the needed changes then deploy it to the Necessry build or personal build


<!--

</br> </br>

#### Applications - [code samples](https://github.com/SAP-samples/cloud-mdk-samples/tree/main/Showcase_Apps)

- FormCell Inline Validation
- Home Screen Widget

-->
