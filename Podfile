use_frameworks!

workspace 'ResourceApp'
project 'ResourceApp/ResourceApp'

abstract_target 'Shared' do
  inhibit_all_warnings!

  pod 'R.swift.Library', :git => '../R.swift.Library'# for CI builds
  # pod 'R.swift.Library', :path => '../R.swift.Library', :branch => 'master'

  target 'ResourceApp' do
    platform :ios, '9.0'

    pod 'SWRevealViewController'
  end
  target 'ResourceAppTests' do
    platform :ios, '9.0'

    pod 'SWRevealViewController'
  end
  target 'ResourceApp-tvOS' do
    platform :tvos, '9.0'
  end
end

