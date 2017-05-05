# clean-panamera-ios
The purpose of this project is to have a model of what is a clean architecture for us for Panamera Project.

What's the clean architecture for us?
- Navigation helper / Storyboard helper -> Routers / Flow controllers
- Realm or CoreData? -> Implement Persistence layer (protocol)
- Support offline mode? Views should be made from persistence, not from backend
- RxSwift with persistence layer
- Replace storyboards with XIBs or layout code
- Cache policy
- MVVM or MVP
- Singetons (managers) and Helpers as DI (for example, persistence, network, tracking)
