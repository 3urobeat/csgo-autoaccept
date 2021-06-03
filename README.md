# csgo-autoaccept
This C# script automatically accepts CS:GO matches for you by analyzing your screen every 4 seconds and moving your mouse when it detects the 'Accept' button.  
Since this script does not interfere with any game files it should be completely VAC safe.  

![Screenshot](https://raw.githubusercontent.com/HerrEurobeat/csgo-autoaccept/master/.github/img/showcase.png)  

Note: This script sadly **only supports Windows** at the moment as I was not able to find any method to move and click with the mouse on Linux.  


## Download
**Easy way:**  
Head over to the [release section](https://github.com/HerrEurobeat/csgo-autoaccept/releases/latest) and download the latest `.exe`.  
  
> Be aware that the Windows Defender likes to throw false-positives. While testing this `.exe` got flagged as a trojan multiple times even when building it directly on Windows.  
VirusTotal Scan: https://www.virustotal.com/gui/file/37577c0492b7b7a04bca548ac798263a7137d3b2bd56c32b1cb112c6ca7f069e/detection  


**Slightly harder way if you don't trust the exe compiled by me:**  
Make sure to have the latest .NET Core SDK installed: https://dotnet.microsoft.com/download/dotnet/5.0  
With the SDK installed you can now compile this project yourself.  
Take a look at this comment if you want to compile it without having an IDE like Visual Studio or MonoDevelop installed: https://stackoverflow.com/a/18286923  

## Usage  
Start the script by executing the `.exe`.  
A terminal window will appear and the script will start scanning your screen every 4 seconds.  
Open CS:GO and queue for a match. The script will automatically accept it for you.  
  
When you are in the loading screen you can close the terminal window.  
If not everyone accepted just leave the script open and it will continue scanning.  

> The game must be on your Primary Display and focused. If you minimze the game the script won't work.  
