# NetworkLibrary
NetworkLibrary is An Android library for fast and easy access to Retrofit.

# Retrofit
Type-safe HTTP client for Android and Java by Square, Inc.

# Installation
* **Gradle**

Add jitpack.io to your root gradle file (project level) :
```sh
allprojects {
 	repositories {
 		...
 		maven { url 'https://jitpack.io' }
 	}
 }
```
Add the **dependency** in your app **build.gradle**
```sh
dependencies {
   implementation 'com.github.ahmedatefabd:RetrofitLibrary:2.0'
}
```
* **Maven**

Add the JitPack repository to your build file
```sh
<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
```
Add the dependency
```sh
<dependency>
	    <groupId>com.github.ahmedatefabd</groupId>
	    <artifactId>RetrofitLibrary</artifactId>
	    <version>Tag</version>
	</dependency>
```
* ### Usage
```sh
ApiClient.getClient(BASE_URL).create(ApiInterface.class);
```
