6998GoogleMapsFramework
=======================

Framework needed for 699807 HW 1 assignment

## Dependencies
      

## Methods
- **`+(void) nearestVenuesForLatLong:(CLLocationCoordinate2D)latLong withinRadius:(double)radius forQuery:(NSString *)query googleMapsAPIKey:(NSString *)apiKey searchCompletion:(void(^)(NSMutableArray *results))completionHandler`**

- Returns an array of Venue Objects for a 2d lat lon, a radius (in meters) for a search query
 The result of this query will be provided in the completion block. If the array is NULL, the request has failed.
