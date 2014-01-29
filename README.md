6998GoogleMapsFramework
=======================

Framework needed for 699807 HW 1 assignment

## Dependencies
      

## Methods
```objective-c
+(void)nearestVenuesForLatLong:(CLLocationCoordinate2D)latLong withinRadius:(double)radius forQuery:(NSString *)query queryType:(NSString *)type googleMapsAPIKey:(NSString *)apiKey searchCompletion:(void (^)(NSMutableArray *results))completionHandler
```

- Returns an array of NSDictionary (like a java hashmap, or javascript JSON object) Objects for a 2d lat lon, a radius (in meters) for a search query
 The result of this query will be provided in the completion block. If the array is NULL, the request has failed.
 
 - Query string refers to the query to search for i.e Chipotle, or Mexican food in midtown manhattan, or broadway theaters. Multi word query strings should be formatted as:
 ```objective-c
      NSString *multiPartQuery = @"my+first+word"";
 ```
 - A type parameter has been added as well. A type is 'restaurant' or 'hotel', etc...    
 
 Refer to google API documentation for any more questions... https://developers.google.com/places/documentation/search
 
