
# MadridShops

MadridShops will shows you
the most popular shops in Madrid. It displays a map with the shop’s location in it and a list of shops. You can browse to the detail of a selected shop.

# Requirements

* Xcode 9 (Should work with Xcode 8)
* Swift 4
* iOS 10.0 (Because of using NSPersistentContainer. If you like to use a previous iOS version, just change CoreDataStack class)

# Cocoapods

* Fillable: Completely customizable progress based loaders drawn using custom CGPaths written in Swift
* Kingfisher: Kingfisher is a lightweight, pure-Swift library for downloading and caching images from the web
* SwiftyJson: SwiftyJSON makes it easy to deal with JSON data in Swift.

# MVC
* Interactor - Contains the application business logic for a specific use case
   * DownloadCityDataInformationInteractor: Retrieve json from an url and parse it to CityDataInformation
   * SaveCityDataInformationInteractor: Save data information in Core Data
   * SaveCityDataInformationImagesInteractor: Save images in disk with KingFisher library
   * ExecuteOnceInteractor: Check if data was store in CoreData
   * SetExecuteOnceInteractor: Set a flag data has been persisted
 
 * Model
   * CityDataInformation: Shop and Activity information
   * ShopCD: Shop CoreData entity
   * ActivityCD: Activity CordeData entity
 
# Bonus

* Activities: As a bonus, we have added Madrid’s activities. Now you can search for things to do in Madrid



