# Maven Repo
一个公开的 Maven Repo

## 引入
```groovy
allprojects {
    repositories {
        // ...
        maven { url 'https://raw.githubusercontent.com/LimeEyewind/repo/master' }
    }
}
```