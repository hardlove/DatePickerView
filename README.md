# DatePickerView
日期选择器

<video width="658" height="444" src="DatePickerView/device-2017-03-11-222019.mp4" poster="http://www.youname.com/images/first.png" autoplay="autoplay"></video>

# How to

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

gradle
maven
sbt
leiningen
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency

	dependencies {
	        compile 'com.github.hardlove:DatePickerView:v1.0'
	}
Share this release:

TweetLink
That's it! The first time you request a project JitPack checks out the code, builds it and serves the build artifacts.

If the project doesn't have any GitHub Releases you can use the short commit hash or 'anyBranch-SNAPSHOT' as the version.

See also

Documentation

Private Repositories
