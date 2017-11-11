# BB-Weather-Vacation
To use this module, add it to the modules array in the config/config.js file:

modules: [
	{
		module: "currentweather",
		
		position: "top_right",	// This can be any of the regions.
		
									// Best results in left or right regions.
		
		config: {
			
			// See 'Configuration options' for more information.
			
			location: "Amsterdam,Netherlands",
			
			locationID: "", //Location ID from http://openweathermap.org/help/city_list.txt
			
			appid: "abcde12345abcde12345abcde12345ab" //openweathermap.org API key.
		}
	}
]
