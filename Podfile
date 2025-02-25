# Uncomment the next line to define a global platform for your project
platform :ios, '13.0'

target 'AppScreenshots' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for AppScreenshots
  
# 布局约束
pod 'SnapKit'
# 动画库
pod 'pop'
# HUD
pod 'SVProgressHUD'
# 键盘管理
pod 'IQKeyboardManagerSwift'
# 网络请求
pod 'Alamofire'
# 谷歌联盟广告
#pod 'Firebase/AdMob'
# 弹出框
pod 'ContextSheet-Swift'

## 友盟统计标准SDK，含IDFA
#pod 'UMengAnalytics'
## U-Share SDK UI模块
#pod 'UMengUShare/UI'
## 集成新浪微博
#pod 'UMengUShare/Social/Sina'
## 集成微信
#pod 'UMengUShare/Social/WeChat'
## 集成QQ
#pod 'UMengUShare/Social/QQ'
## 集成腾讯微博
#pod 'UMengUShare/Social/TencentWeibo'
## 加入IDFA获取
#pod 'UMengUShare/Plugin/IDFA'

end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings["IPHONEOS_DEPLOYMENT_TARGET"] = "13.0"
    end
  end
end
