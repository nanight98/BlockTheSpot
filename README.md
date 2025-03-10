

<center>
    <h3 align="center">okay yeah</h3>
    <h3 align="center">it's finished</h3>
</center>

<center>
    <h4 align="center">A multi-purpose adblocker and skip-bypass for the <strong>Windows</strong> Spotify desktop application.</h4>
    <h5 align="center">Support Spotify by purchasing premium</h5>
    <p align="center">
        <strong>Last updated:</strong> 27 December 2021<br>
        <strong>Last tested version:</strong> 1.1.74.631.g0b24d9ad
    </p> 
</center>

#### Important checks before installing:
0. Update Windows, update Spotify and update BlockTheSpot
1. Go to "Windows Security" -> "Virus & Threat Protection"
2. Click "Allowed threats" -> "Remove all allowed threats"

### Features:
* Blocks all banner/video/audio ads within the app
* Retains friend, vertical video and radio functionality
* Unlocks the skip function for any track
* Now supports the new Alpha version (New UI)

:warning: This mod is for the [**Desktop Application**](https://www.spotify.com/download/windows/) of Spotify on Windows only and **not the Microsoft Store version**.

### Installation/Update:
* Just download and run [BlockTheSpot.bat](https://raw.githack.com/nanight98/BlockTheSpot/master/BlockTheSpot.bat)  

or

* Run The following command in PowerShell:
```ps1
Invoke-WebRequest -UseBasicParsing 'https://raw.githubusercontent.com/nanight98/BlockTheSpot/master/install.ps1' | Invoke-Expression
```

or

1. Browse to your Spotify installation folder `%APPDATA%\Spotify`
2. Rename `chrome_elf.dll` to `chrome_elf_bak.dll`
2. Download `chrome_elf.zip` from [releases](https://github.com/mrpond/BlockTheSpot/releases)
3. Unzip `chrome_elf.dll` and `config.ini` 

### Uninstall:
* Just run uninstall.bat
or
* Reinstall Spotify 

### Known Issues:  
* You may face issue [#150](https://github.com/mrpond/BlockTheSpot/issues/150). It can be fixed by enabling the experimental feature when using `BlockTheSpot.bat`.    
* We support the last 2 versions of Spotify (latest + previous) only. Please check it before opening an issue.

### Additional Notes:  
* Remove "Upgrade" Button [#83](https://github.com/mrpond/BlockTheSpot/issues/83) and Remove "Ad Placeholder" [#150](https://github.com/mrpond/BlockTheSpot/issues/150) only works when you use any of the auto installation methods and press `y` when prompted.  
* "chrome_elf.dll" gets replaced by the Spotify installer each time it updates, hence why you'll probably need to apply the patch again when it happens
* [Spicetify](https://github.com/khanhas/spicetify-cli) users will need to reapply BlockTheSpot after applying a Spicetify patches.
* If the automatic install/uninstall scripts do not work, please contact [nanight98](https://github.com/nanight98)
