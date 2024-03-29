# iOS assignment | Weather

### **High-level review of the application**
- Created file structure as per features and includes files(view, viewmodel, subviews..) into one group
- Used MVVM architecture with SOLID principles
- Made project unit testable using dependency injection/ dependency inversion whereever applicable.
- Improved test coverage for the all viewmodels
- Used composable views to build nested screens
- I would recommond usage of SPM for third party libraries.
- Image loading asynchronously Not caching into current application.
- I would recommond the modular structure based on feature.
- I would recommond Use Liniting tools eg. SwiftLint

### **Things that can be improved**
- Support of accessibility
- Introduce XCUItest
- Modularization
- Dark theme support
- dynamic fonts
- Introduce loading indicator
- Introduce internet connectivity and failure and retry screens
- Introduce async/await for better performance and clean architecture.
- Image Cached Or might be use third party framework
- Network API calling framework if necessory
- Architecture based on design patterns
- Error Handling more effective way.

## **This application works online and offline and iphone and ipad. In iphone stackview orientation changed but into ipad you can see the only 1 view. Application only fetch 1 time data when there is an internet connection. after that its always fetch from database. Its a very simple sync logic but we can improve this logic to last fetch time or update time according to functionalities. Also there is no image caching and offline store for image if you open application without internet you can see placeholder image instead of real image.**

##### **Notes: The project works with Xcode 14.0 and above iOS 16 (Not sure about lower version might some apple api won't work) and the language used is Swift. Must run project into simulator Or device not into swiftUI preview. Also Added Realm database as pods due to Realm's SPM configuration has some issue into test targets.**

### **Let me know if you still have difficulties to run code. or send me an email at vishalkalola196@gmail.com**
