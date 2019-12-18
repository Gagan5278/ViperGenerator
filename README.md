# ViperGenerator
Demo for creating Viper Template
When you decide to use VIPER architecture in your project, it is very hard to  create new modules, because every time you need create at least 5 files for each module. This repo can solve problem. Just install as below and you are done. 

## How to install

### Using script (easy)
Only need execute this command in terminal:
```swift
sudo swift install.swift
```
You should be this output message:

 _ ✅  Template installed succesfully 🎉. Enjoy it 🙂 _

If all it's ok you now could find your template in Xcode.

### Manual
Go to Application folder, browse to the Xcode application icon. Right-click it and choose 'Show Package Contents'. Then browse to:
`Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/Xcode/Templates/Project Templates/iOS/Application` and add "Module VIPER.xctemplate" file. Now you can find your template in Xcode.

Now Create a new file from Xcode, you will have below

<img width="937" alt="Screenshot" src="https://user-images.githubusercontent.com/2304583/71085762-e34a4200-21a0-11ea-80f3-d0fe8dc0b896.png">
