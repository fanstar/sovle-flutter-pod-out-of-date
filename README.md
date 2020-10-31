# sovle-flutter-pod-out-of-date
Error output from CocoaPods: ↳      [!] Automatically assigning platform `iOS` with version `9.0` on target `Runner` because no platform was specified. Please specify a     platform for this target in your Podfile. See `https://guides.cocoapods.org/syntax/podfile.html#platform`.  Error: CocoaPods's specs repository is too out-of-date to satisfy dependencies. To update the CocoaPods specs, run:   pod repo update    Error running pod install Error launching application on iPhone xx.

#How to solve
Remove : 6 Files
  - Podfile.lock
  - Runner.xcworkspace
  - Flutter/App.framework
  - Flutter/flutter_export_environment.sh
  - Flutter/Flutter.framework
  - Flutter/Flutter.podspec
  
 Next: rebuild
 command: flutter run
 
 !!!Sovled
