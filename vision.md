# The current problem #
Today road infrastructure maintenance is reactive in Indianapolis. Requiring citizens to manually report potholes and where they are which is a slow process not addressing fixing the roads fast enough allowing them to deteriorate worse. 

**The vision**
- Develop a real time road monitoring AI system
- Through sensors or cameras this system will be an interconnected platform that can monitor and detect in real time the health of roads.
- Any roads with a certain level of health deterioration will be reported on a custom made application. This can be used by city officials to know exactly which roads are bad, why they are bad, and also see the predicted healths status to know exactly when this road is going to be an issue for drivers. This will allow DPW to allocate resources faster to fix roads quicker.
- This will need a combination of different components.
  1. Road history - how roads change over time
  2. Geospatial data - needed for getting an interconnected layout of the city and road coordinates 
  3. Weather data - for context on to what are factors that causes road deterioration
  4. Traffic data - how much traffic can/will impact the road
  5. maintenance 
- Multiple models will be developed and operate as a unified system.
  1. Road severity model - how bad is this road right now?
  2. A deterioration model - what will the state of road be?
  3. Pothole risk model - Given everything we know about this road, how likely is failure within some future window?
- The interface
  1. A custom made application. This will store the models outputs but be used for creating an interactive interface for users to see the display.
  2. This will include dashboards of hotspots with sever road health, pothole mappings within roads and risk score, as well weather tracking.
  3. This will include an AI assistant for users to ask questions such as "how bad will Meridian street be after this snowstorm occurs"
     - Charts can be generated through NLS. There can be dashboards already made and then a section for when users query charts and graphs are generated through NLS providing users an actual visual representation of the answer to their question with also explainability in human readable language. 
  
