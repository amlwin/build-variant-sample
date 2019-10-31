fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
```

## Choose your installation method:

<table width="100%" >
<tr>
<th width="33%"><a href="http://brew.sh">Homebrew</a></td>
<th width="33%">Installer Script</td>
<th width="33%">Rubygems</td>
</tr>
<tr>
<td width="33%" align="center">macOS</td>
<td width="33%" align="center">macOS</td>
<td width="33%" align="center">macOS or Linux with Ruby 2.0.0 or above</td>
</tr>
<tr>
<td width="33%"><code>brew cask install fastlane</code></td>
<td width="33%"><a href="https://download.fastlane.tools">Download the zip file</a>. Then double click on the <code>install</code> script (or run it in a terminal window).</td>
<td width="33%"><code>sudo gem install fastlane -NV</code></td>
</tr>
</table>

# Available Actions
## Android
### android test
```
fastlane android test
```
Runs all the tests
### android debug
```
fastlane android debug
```
asseble debug
### android release_abb_all
```
fastlane android release_abb_all
```

### android debug_abb_all
```
fastlane android debug_abb_all
```

### android debug_apk_all
```
fastlane android debug_apk_all
```

### android release_apk_all
```
fastlane android release_apk_all
```

### android release_apk_apple
```
fastlane android release_apk_apple
```

### android clean
```
fastlane android clean
```

### android deploy
```
fastlane android deploy
```
Deploy a new version to the Google Play

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
