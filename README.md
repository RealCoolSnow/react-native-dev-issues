# react-native-dev-issues

### 1. issue - Error: spawn ./gradlew EACCES 
fix - 权限问题，在项目目录下使用以下命令即可: chmod 755 android/gradlew

### 2. Mac m1 - pod install Error
fix - 在ios下目录执行:
sudo arch -x86_64 gem install ffi
arch -x86_64 pod install
||
arch -x86_64 pod update && pod install