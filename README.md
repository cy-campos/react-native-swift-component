# react-native-swift-component
A test sandbox to describe steps and gotchas when creating a swift based component using the latest available environments (see dependencies below)

Hello all. This repo will be a first of many things for me. I had to learn how to develop a custom React Native component for iOS with no prior knowledge of RN, Obj-C, and Swift. This is also my first repo on here ever... so woohoo! Also, be forewarned that I am not an expert in iOS development.. so my methods may not be best practices (for now...)

This repo will mainly deal with personal issues I had getting everything set up. Hopefully, this may also help RN noobs, as I found that the available documentation was sporadic and inconsistent at best. I only had about 1 week to learn this stuff..and it was brutal (I'm not that smart ;)). I hope that I will never forget how I did this..and also to help minimize any headaches for anyone else coming into a similar situation. 

Dependencies:
- React Native 0.55
- Xcode 9
- Node Package Manager 3.1.0
- Homebrew (Optional)
- Cocoapods (Optional)
- Expo XDE (Optional)
- Visual Studio Code 1.23 (although any text editor like Atom, Sublime, would suffice)

Assumptions:
- You have admin access to your computer.
- You have experience with programming in general

Difficulties:
- Xcode 9 is not fun. There is a solid reason why this is rated 2 out of 5 stars in the App Store. I did manage to tame this a tad by reformatting my computer and installing a fresh copy prior to tackling RN development.
- Xcode Interface Builder (xib) for the UI caused issues towards the end
- Objective-C was daunting to me, at least compared to my experience in Java and C#
- UI containers within containers..and the pattern of sending data between all of them
