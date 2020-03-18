# Data Used
The data used in this problem will be extracted from 
"https://data.gov.in/resources/all-india-pincode-directory-contact-details-along-latitude-and-longitude"
which is provided by the govenment of India.The data is available in csv format and we will read it in a
pandas dataframe and remove all the fields not related with the two cities in consideration.We shall also
clean the unnecessary columns in the data frame which we donot need and then merge the neighborhoods with
same neighborhood . The latitude and longitude for these locations will be obtained from geopy library in
python. Foursquare api will be used to access the venues and their releated information in the neighborhood
of the locations using their latitude and longitude. 
