a. What this map shows
This web scene shows Catalina Island roads and trails in 3D. The scene is centered on Catalina Island with roads and trails visualized as a red 2D polyline feature.

b. Starting sample (name and link)
This project is based on the Intro to SceneView - Create a 3D map sample. This sample walks readers through how to reference the ArcGIS Maps SDK for JavaScript, load SceneViewer modules and create a 3D view.
Link: https://developers.arcgis.com/javascript/latest/sample-code/intro-sceneview/

c. What I changed
I changed a variety of parameters within the scene, including the camera position, orientation, elevation and zoom. I also changed the page title, added a legend, customized popups highlighting specific fields, and the symbology of the roads/trails layer.

d. Data source (name, URL, which layer type you used, and why you picked it)
Name: Catalina_Roads_Trails, URL: https://services.arcgis.com/RmCCgQtiZLDCtblq/arcgis/rest/services/Catalina_Roads_Trails/FeatureServer/0
The layer chosen for this project is the Catalina Roads & Trails layer published by Los Angeles County. This layer was chosen as it is a good showcase of the island and keeps the extent of the 3D scene limited, allowing for details found in the 3D geometry to be best visualized.

e. Component I added
For this project, I kept the visualization simple and added a legend. This component was chosen to aid with clarity as the nature of the roads/trails layer is not described elsewhere.

f. Problems and what I’d improve next
The next step for this project would be to create a unique values symbolization scheme for the roads/trails layer. Each line has an associated type, meaning roads could be symbolized based on their type. I was unable to figure out that functionality in time for this project.

g. Credits
References for this project include the Intro to SceneView - Create a 3D map sample, the Intro to Feature layer sample, and generative AI. AI was used (unsuccessfully) to research how to customize the symbology of the feature layer.
