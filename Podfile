platform :ios, '10.0'

# Ignore warnings from external libraries
inhibit_all_warnings!

target 'Raivo' do
  use_frameworks!

  # Realm SQLite database handler that supports encryption
  pod 'RealmSwift', '3.13.1'
  
  # To encrypt sensitive data before being synced
  pod 'RNCryptor', '5.0.3'
  
  # Allow access to Secure Enclave
  pod 'Valet', '3.2.3'

  # Deprecated POD that was used for keychain access
  pod 'KeychainSwift'
  
  # A one time password URI parser (for if you scan QR codes)
  pod 'OneTimePassword', '3.1.4'

  # Enables easy form creation for adding and editing passwords
  pod 'Eureka', '5.0.0'
  pod 'ViewRow', '0.6'
  
  # Retrieves, caches and displays images from the web (for issuer logos)
  pod 'SDWebImage', '5.0.2'
  pod 'SDWebImageSVGCoder', '0.2.0'

  # Debug logging (only used in debug builds)
  pod 'SwiftyBeaver', '1.7.0'

  # UI notification banners (e.g. for a notification if you copied an OTP)
  pod 'SwiftMessages', '6.0.2'
  
  # Haptic feedback while e.g. entering PIN code or copying an OTP
  pod 'Haptica', '3.0.0'
  
  # HTTP requests for custom issuer icons
  pod 'Alamofire', '4.8.1'
  
  # Allows encrypted ZIP file creation for OTP exporting
  pod 'SSZipArchive', '2.2.2'
  
  # QRCode generation for data export
  pod 'EFQRCode', '5.0.0'
  
  # Easy view animations (like flikkering error messages)
  pod 'Spring', :git => 'https://github.com/MengTo/Spring.git'

end