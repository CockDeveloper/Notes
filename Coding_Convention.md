# Coding Convention

## Naming Convention
Letter case-separated words:
* camelCase
* PascalCase
* snake_case

## Constants 
1.Syntax:
* Const external impelement class:  \<PREFIX\>\<DOMAIN_NAME\>_\<NAME_CONST\>
* Const in impelement class:        \<PREFIX\>\<DomainName\>_\<NameConst\>    or: \<PREFIX\>\<DomainName\>\<NameConst\>

2.Require:
* Const external impelement class:  UPPER_CASE
* Const in impelement class:        UPPER_CASE and PascalCase

3.Example:
```objective-c
// Objecive-C
// https://developer.apple.com/documentation/uikit/uikit_constants
// https://developer.apple.com/documentation/uikit/uikit_string_enums?language=objc
#define UIKIT_STRING_ENUMS
```
```swift
// Swift
// https://developer.apple.com/documentation/uikit/uikit_constants
// https://developer.apple.com/documentation/uikit/uikit_string_enums
var UIKIT_STRING_ENUMS: Int32 { get }
```

```objective-c
// Objecive-C
// https://developer.apple.com/documentation/foundation/nsurlerrordomain?language=objc
const NSErrorDomain NSURLErrorDomain;
// https://developer.apple.com/documentation/quartzcore/kcamediatimingfunctionlinear?language=objc
const CAMediaTimingFunctionName kCAMediaTimingFunctionLinear;
```
```swift
// Swift
// https://developer.apple.com/documentation/foundation/nsurlerrordomain
let NSURLErrorDomain: String
// https://developer.apple.com/documentation/quartzcore/camediatimingfunctionname/1521943-linear
static let linear: CAMediaTimingFunctionName
```

## Reference Document
https://en.wikipedia.org/wiki/Naming_convention_(programming)

https://viblo.asia/p/coding-convention-psr-va-coding-standard-in-framgia-djeZ1amQZWz (Vietnamese)

https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Conventions/Conventions.html

http://google.github.io/styleguide/objcguide.html

https://google.github.io/swift/

https://swift.org/documentation/api-design-guidelines/#naming

