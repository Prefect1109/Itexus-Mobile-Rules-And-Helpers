# The Official Itexus iOS project structure.

```
Project Name
.
├── Classes
│   ├── Application
│	│	├── AppDelegate.swift
│	│	├── Info.plist
│	│	└── R.generated.swift
│	│
│   ├── Common
│	│	├── Extensions
│	│	│	├── Reactive.swift
│	│	│	└── UIView
│	│	│		├──	UIView+Border.swift
│	│	│		└──	UIView+Animation.swift
│	│	├── Helpers
│	│	├── Network
│	│	│	├── Base
│	│	│	│	├── NetworkService.swift
│	│	│	│	└── NetworkUtils.swift
│	│	│	├── Plugins
│	│	│	└── Moya
│	│	│		└── Auth
│	│	│			├── Models
│	│	│			├── AuthService.swift
│	│	│			└── AuthAPI.swift
│	│	├── Protocols
│	│	└── Credentials.swift
│   ├── Modules
│	│	└── Auth
│	│		├── Auth.storyboard
│	│		├── LogIn
│	│		│	├── LogInViewController.swift
│	│		│	├── LogInViewModel.swift
│	│		│	├── LogInElements.swift
│	│		│	└── LogInConfigurator.swift
│	│		└── SignUp
│	│
│   ├── Views
│	│	└── Auth
│   └── UseCases
├── Resources
│   ├── Assets.xcassets
│   ├── LaunchScreen.storyboard
│   ├── Localizable.strings
│   └── Colors.xcassets
└──
```
