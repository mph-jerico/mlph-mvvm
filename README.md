add this on your build file

allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  add dependency
  
  dependencies {
		implementation 'com.github.jmaming:mlph-mvvm:Tag'
	}

