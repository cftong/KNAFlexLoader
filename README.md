# AFlexLoader

## A dylib Loader for [Flex](https://github.com/Flipboard/FLEX), You can use it to analyse 3rd-party apps without sourcecode

### Usage

> * 1.theos requested
> * 2.edit the Makefile, change the THEOS_DEVICE_IP to your iDevice's ip
> * 3.make package install
> * 4.open your iDevice's Settings, find out the AFlexLoader, click into it, and open the App which you want to analyse

安装遇到的问题

dpkg: dependency problems prevent configuration of org.swiftc.aflexloader:
 org.swiftc.aflexloader depends on preferenceloader (>= 2.2); however:
  Package preferenceloader is not installed.
 org.swiftc.aflexloader depends on applist (>= 1.5.11); however:
  Package applist is not installed.

在管理——软件源——Bigboss里找到preferenceloader，这是Cydia的依赖包，安装就可以。
