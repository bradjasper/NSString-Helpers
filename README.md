NSString-Helpers
================

A category on NSString for validation and manipulation.

#Validation methods

```objc
+ (BOOL)isEmpty:(NSString *)string;
+ (BOOL)isUInteger:(NSString *)string;

- (BOOL)isMatchesRegExp:(NSString *)regExp;
```

#Manipulation methods

```objc
+ (NSString *)trim:(NSString *)string;
```

Demo
====

Clone project and run it. You can find examples of usage at NSSHTestViewController.m.

Compatibility
=============

This class has been tested back to iOS 6.0.

License
=======

This code is released under the MIT License. See the LICENSE file for
details.