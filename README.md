# Steam Account Switcher (v2)
This is a fork of [W3D3's excellent repo](https://github.com/W3D3/SteamAccountSwitcher2).

I just fixed the bugs that prevented me from using it.


### Download
You can download the source code and compile it.
Or, download the pre-compiled installer from [GitHub Releases](https://github.com/Ogglord/SteamAccountSwitcher2/releases)

### Whats added
- Logging of unhandled exceptions to file ([Serilog](https://serilog.net/) library)
- Disabled the steam status (the API seems to be offline)
- Disabled the update check (the URL is offline)
- Making sure the program handles the steam path without case sensitivity
- Making sure the program works for new users, there was a bug that occured for fresh installs only

### More info
Please report any bugs on github here or at W3D3s repository directly