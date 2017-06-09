// To disable Xcode 8 log. Edit schema.

OS_ACTIVITY_MODE = disable

// Print HTTP Body for Alamofire request
// Swift 3 +

print(NSString(data: (response.request?.httpBody)!, encoding: String.Encoding.utf8.rawValue))


// Back button item
override func prepareForSegue(segue: UIStoryboardSegue, sender: AnyObject?) {
let backItem = UIBarButtonItem()
backItem.title = "Something Else"
navigationItem.backBarButtonItem = backItem // This will show in the next view controller being pushed
}

// Validate iOS version
if #available(iOS 10.0, *) {
	// use the feature only available in iOS 10            
}

// Allow HTTP connections
<key>NSAppTransportSecurity</key>
<dict>
    <key>NSAllowsArbitraryLoads</key>
    <true/>
</dict>
