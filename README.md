### Navigation Setup

`npm install @react-navigation/native @react-navigation/stack @react-navigation/bottom-tabs react-native-screens react-native-gesture-handler @react-native-async-storage/async-storage`

App Navigator (Root)
├── Onboarding Stack (First-time users)
├── Auth Stack (Unauthenticated users) 
└── Main Tab Navigator (Authenticated users)
    ├── Home Tab
    ├── Profile Tab  
    └── Settings Tab