# UHF-R2000

**Add file ti libs
1.DeviceAPI_ver20210924
2.jxl
3.xUtils-2.5.5


**add dependencies to gradle module app
dependencies {
    implementation fileTree(include: ['*.jar'], dir: 'libs')
    implementation files('libs/xUtils-2.5.5.jar') //implementation files('org.xutils:xutils:2.5.+')
    implementation files('libs/jxl.jar')
    implementation (files("libs/DeviceAPI_ver20210924.aar"))
    }
