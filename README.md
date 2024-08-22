Description: The user will provide the layer they wish to replace, and the layer they wish to replace it with. Then the notebook will loop through all the maps searching for the provided layer, and it will replace it with the other provided layer.
    
Created on: 5/21/24

Purpose: This is to streamline the ability to replace layers in webmaps in ArcGIS Online. 

Authored By: Joe Guzi

Previous Production Date: 7/8/24

Production Date: 7/18/24

Note: You can use the ArcGIS Online Web Map Services Audit notebook, below, to get a preview of all of the maps that will be updated by this notebook. Simply run the notebook then filter on the layer you want to replace, and you will have an inventory of all of the maps that will be updated: https://www.arcgis.com/home/item.html?id=72ce7ff61fc5480d850ed68de29f1d9c 

- 7/3/24 - Minor update for proofreading.
- 7/8/24 - Added sign in option "Connect with current AGO Credentials to this organization" to allow the notebook to be uploaded to AGO as a hosted notebook and run from AGO.
- 7/18/24 - rearranged the order of the remove and readd layers to accomodate hosted feature layers with multiple layers. It does not work if the layers are grouped. 
- 8/22/24 - Reworked the code to based on some inspiriation from Glen Bambrick.
    - You can only replace the layers in a webmap using URLs
    - This new method has a more streamlined approach to handling the order of the layers in the WebMap
    - Thank you Glen!
