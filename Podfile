# Uncomment the next line to define a global platform for your project
platform :ios, '12.0'

use_frameworks!

target 'GEReelsMapView' do
  # Comment the next line if you don't want to use dynamic frameworks
  # use_frameworks!

  # Pods for GEReelsMapView
  pod 'BlocksKit', '~> 2.2'
  pod 'SVGKit', '~> 3.0'
end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings["IPHONEOS_DEPLOYMENT_TARGET"] = "12.0"
    end
  end
end
