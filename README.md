# iparepackage
A perl script for ipa repackage, working with mac xcrun tool. using by [ipapub](https://github.com/rayer4u/ipapub)/[ipasign](https://github.com/rayer4u/ipasign)
##使用方法
1. 拷贝脚本到iphoneos的工具目录*/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin*
2. 运行脚本进行打包
`xcrun RePackageApplication ...`

##参考
><http://stackoverflow.com/questions/26497863/xcode-6-1-error-while-building-ipa-using-testflight-app>
6.1的打包patch。以及xcrun的扩展

><http://stackoverflow.com/questions/15634188/resigning-an-ios-provisioning-profile>
重签名相关

><https://github.com/maciekish/iReSign>
一个图形化的mac重打包工具
