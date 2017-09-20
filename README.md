
#MadridShops

MadridShops will shows you
the most popular shops in Madrid. It displays a map with the shop’s location in it and a list of shops. You can browse to the detail of a selected shop.

#Requirements

* Xcode 9 (Should work with Xcode 8)
* Swift 4
* iOS 10.0 (Because of using NSPersistentContainer. If you like to use a previous iOS version, just change CoreDataStack class)

#Cocoapods


* Fillable: Completely customizable progress based loaders drawn using custom CGPaths written in Swift
* Kingfisher: Kingfisher is a lightweight, pure-Swift library for downloading and caching images from the web
* SwiftyJson: SwiftyJSON makes it easy to deal with JSON data in Swift.

#
* Interactor - Contains the application business logic for a specific use case
* * DownloadCityDataInformationInteractor: Retrieve json from an url and parse it to CityDataInformation
** DownloadCityDataInformationAndSaveItInteractor: Execute the DownloadCityDataInformationInteractor and save the information in CoreData
** ExecuteOnceInteractor: Check if data is persisted
** SetExecuteOnceInteractor: Set that data has been persisted
** ReachabilityInteractor: Check internet reachability

#Bonus

* Activities: As a bonus, we have added Madrid’s activities. Now you can search for things to do in Madrid



