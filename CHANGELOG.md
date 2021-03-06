## 0.2.8

##### Breaking

None.

##### Enhancements

None.

##### Bug Fixes

* Fixed issue where certain Swift files wouldn't be parsed.  
  [JP Simard](https://github.com/jpsim)
  [#18](https://github.com/jpsim/sourcekitten/issues/18)

## 0.2.7

##### Breaking

None.

##### Enhancements

None.

##### Bug Fixes

* Fixed improper UTF8 parsing of MARK comments.  
  [JP Simard](https://github.com/jpsim)
  [realm/jazzy#131](https://github.com/realm/jazzy/issues/131)

## 0.2.6

##### Breaking

None.

##### Enhancements

* Added CHANGELOG.md.  
  [JP Simard](https://github.com/jpsim)
  [realm/jazzy#125](https://github.com/realm/jazzy/issues/125)

* Include parse errors in the JSON output.  
  [JP Simard](https://github.com/jpsim)
  [#16](https://github.com/jpsim/sourcekitten/issues/16)

##### Bug Fixes

* Fixed crash when files contained a declaration on the first line.  
  [JP Simard](https://github.com/jpsim)
  [#14](https://github.com/jpsim/sourcekitten/issues/14)

* Fixed invalid JSON issue when last file in an Xcode project failed to parse.  
  [JP Simard](https://github.com/jpsim)

* Fixed crash when attempting to parse the declaration of `extension Array`.  
  [JP Simard](https://github.com/jpsim)
  [realm/jazzy#126](https://github.com/realm/jazzy/issues/126)
