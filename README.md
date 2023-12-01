Group Name: Project Group 45

Group Member: UNIs: [cg3342, jf3628]

Project Description:
Examples of using analytical tools to tackle real-world problems for loading, editing, understanding, and visualizing data to find suitable apartments.

Part 1: Data Preprocessing
Fetch data chunk by chunk from api_endpoint and save each chunk of data as local json files, ignore data except the following column [ZIPCODE and geometry].

Part 2: Storing Data
Create SQL tables directly from using to_postgis function and add data to the nyc_rents table.

Part 3: Understanding Data
Roughly judge the livability of an area by the number of complaints and trees. Areas with more trees and fewer complaints are more livable. Check the rent for the corresponding zip code.

Part 4: Visualizing Data
Generate a boxplot of the number of complaints and rent to determine whether there is a direct relationship between rent and the number of complaints, and generate a comparison table between the willingness to plant trees and the actual number of trees.

Datasets:
Shapefiles of NYC’s zip codes with geometric boundary data from https://drive.google.com/drive/folders/1P89KAFAUAHVZsEcyDYVfD1L7pMeGBvIO?usp=sharing.
Historical monthly average rents by zip code from Zillow from https://drive.google.com/file/d/19h6qhJHjxyyNd4DML7pbf1pJGavQed0s/view?usp=sharing.
Historical data from NYC Open Data on https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9 and https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/pi5s-9p35.