
#  Rules for Swift language

This document explains Swift language rules, which are accepted by Itexus iOS team

## Classes

###  Class defiition

```Swift
class Name {
// [Enter]
// Code
// [Enter]
}
```

### Properties

```Swift
class Name {

  @IBOutlet weak var button: UIButton!
  @IBOutlet weak var loginTextField: UITextField!
  // [Enter]
  fileprivate lazy var viewModel = FirstViewModel()
  fileprivate lazy var loginModel = LoginViewModel()

}
```

### Methods

```Swift
// Note: Something[no space]:[single space]SomeType
class ClassName: BaseClassName  {

  override func name() -> SomeParam {
    super.name()
    // [Enter]
    // Code
    // [Enter]
    return param
    // [Enter]
  }
  // [Enter]
  func otherfunc() {
    // [Enter]
    // Code
    // [Enter]
  }

}
```

## Control Flow

### if else

```Swift
    if a < 10 {
        // Code
    } else {
        // Code
    }
```

### switch

```Swift
    switch name {
        case 0:
            // Code
        default:
            // Code
    }
```

## Primitive operations

```Swift
    a = (b + c) / d
```

## Coments

### TODOs
```Swift
//TODO: - Some work
```

### MARKs
```Swift
//MARK: - Private
```
