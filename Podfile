# Uncomment the next line to define a global platform for your project
platform :ios, '11.0'

source 'https://github.com/CocoaPods/Specs.git'
source 'https://bitbucket.org/cybavo/Specs_512.git'

target 'WalletSDKDemo' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for WalletSDKDemo
  pod 'GoogleSignIn', '4.4.0'
  pod 'SwiftEventBus', :tag => '5.1.0', :git => 'https://github.com/cesarferreira/SwiftEventBus.git'
  pod 'Toast-Swift', '~> 4.0.0'
  pod 'CYBAVOWallet', '~> 1.2.0'
  pod 'PKHUD', '~> 5.0'

  target 'WalletSDKDemoTests' do
    inherit! :search_paths
    # Pods for testing
  end
end
