# ServiceData

### Package Description :
ServiceData is an HTTP networking library written in Swift which can download different types of data.

### Features List :
- can download different types of items json, data..

#### Usage :
To use `ServiceData`, For example:

```swift
// swift-tools-version:5.2

import ServiceData

struct UserVM {
    
    func fetchData(completion: ([Users]) -> ()) {
        ServiceData.fetchGenericData(from: "url", completion: completion)
    }
    
}

```
## Author:

Mubarak Alseif 👨‍💻
info@easycode.co
