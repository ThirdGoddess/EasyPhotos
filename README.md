
# Fork，修改安卓高版本视频预览崩溃问题

安卓高版本，点击视频预览崩溃，在此基础上修改，旧代码业务需要

# 依赖
```java
dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url 'https://jitpack.io' }
		}
}
```

```java
dependencies {
	        implementation 'com.github.ThirdGoddess:EasyPhotos:v3.1.6'
}
```

---

# 源github信息
https://github.com/HuanTanSheng/EasyPhotos

