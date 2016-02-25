source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'
use_frameworks!

pod 'RESideMenu', '~> 4.0.7'
pod 'Alamofire', '~> 3.0'
pod 'SwiftyJSON', :git => 'https://github.com/SwiftyJSON/SwiftyJSON.git'
pod 'SVProgressHUD', '~> 2.0-beta8'
pod 'Neon', '~> 0.0.3'
pod 'Firebase', '>= 2.5.0'
pod 'CardIO', '~> 5.3.1'
pod 'Stripe', '~> 6.2.0'
pod 'VideoSplashKit', '~> 1.1.0'
pod 'TextFieldEffects', '~> 1.1.0'
pod 'UIColor_Hex_Swift', '~> 1.8'
pod 'KeychainSwift', '~> 3.0'
pod 'MZFormSheetPresentationController', '~> 2.3.0'
pod 'PasscodeLock', '~> 1.0.1'
pod 'BEMCheckBox', '~> 1.0.0'
pod 'SwiftGifOrigin', '~> 1.5.2'
pod 'CWStatusBarNotification', '~> 2.3.4'
pod 'Koloda', '~> 2.0.10'


post_install do |installer|
    `find Pods -regex 'Pods/pop.*\\.h' -print0 | xargs -0 sed -i '' 's/\\(<\\)pop\\/\\(.*\\)\\(>\\)/\\"\\2\\"/'`
end