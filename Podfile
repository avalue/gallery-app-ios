plugin 'cocoapods-keys', {
  :project => 'Gallery',
  :keys => [
    'GallerySpaceId',
    'GalleryAccessToken'
  ]}

source 'https://github.com/CocoaPods/Specs'
source 'https://github.com/contentful/CocoaPodsSpecs'

platform :ios, '8.0'

inhibit_all_warnings!

target 'Gallery' do

#use_frameworks!

pod 'ContentfulDialogs'
pod 'ContentfulPersistence'
pod 'ContentfulStyle', :head

end

target 'GalleryTests' do

pod 'FBSnapshotTestCase'

end

