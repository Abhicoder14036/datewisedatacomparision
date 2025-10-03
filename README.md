# datewisedatacomparision
This is a GIS project that allows users to select a state and district, and then choose a date range (from and to). After that, the user can select the layer they want to compare and hit the Analyze button. The data will be displayed date-wise through a chart, and on the map, the corresponding points will be highlighted with identifiers.


Service based on your webservice, which is published on the server manager.

 const layerURLs = {
                "Bank Branch": "Add layer for Bank Branch",
                "ATM": "Add layer for ATM",
                "Bank Mitra": "Add layer for Bank Mitra",
                "IPPB": "Add layer for ippb",
                "CSC": "Add layer for CSC",
                "Post Office": "Add layer for Post Office"
            };

  const stateLayer = new FeatureLayer({
                url: "Add layer for State",
                outFields: ["stname"]
            });

      const districtLayer = new FeatureLayer({
                url: "Add layer for the District",
                outFields: ["dtname", "stname"]
            });      
           
          
