# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'MedeeView-Lab' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for MedeeView-Lab
  #pod 'GoogleMobileVision/FaceDetector'
  pod 'Firebase/Core'
  pod 'Firebase/MLVision'
  pod 'Firebase/MLVisionFaceModel'
  
  # Fix Build on ARM
  post_install do |installer|
    installer.pods_project.build_configurations.each do |config|
      config.build_settings["EXCLUDED_ARCHS[sdk=iphonesimulator*]"] = "arm64"
    end
  end

  target 'MedeeView-LabTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'MedeeView-LabUITests' do
    # Pods for testing
  end

end

target 'MedeeView-Lab WatchKit App' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for MedeeView-Lab WatchKit App

end

target 'MedeeView-Lab WatchKit Extension' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for MedeeView-Lab WatchKit Extension

end
