# clean-panamera-ios
The purpose of this project is to have a model of what is a clean architecture for us for Panamera Project.

What's the clean architecture for us?
- Navigation helper / Storyboard helper -> Routers / Flow controllers
http://clean-swift.com/routing-in-clean-swift/
https://medium.com/monitisemea/routing-with-mvvm-on-ios-f22d021ad2b2

- Realm or CoreData? -> Implement Persistence layer (protocol)
https://medium.com/@dcordero/data-sources-in-swift-or-how-to-avoid-that-this-new-trendy-persistency-framework-determines-the-5472fcb75eda

- Support offline mode? Views should be made from persistence, not from backend
- RxSwift with persistence layer
- Replace storyboards with XIBs or layout code

- Cache policy
- MVVM or MVP
https://cocoacasts.com/series/model-view-viewmodel-and-swift/
https://cocoacasts.com/testing-view-models-with-model-view-viewmodel/

- Singetons (managers) and Helpers as DI (for example, persistence, network, tracking)
http://www.jessesquires.com/refactoring-singletons-in-swift/
