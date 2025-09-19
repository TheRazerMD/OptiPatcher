# OptiPatcher
An **ASI Plugin for OptiScaler** for exposing DLSS/DLSS-FG inputs without spoofing in **supported games**.  

> [!NOTE]
> * It should help Intel Arc users the most because with newer versions of Unreal Engine spoofing has issues, causing `D3D12 not supported` errors.  
> * Now with DLSSG patching, all AMD/Intel users benefit too.  

## Currently supported games
* Check the [Game Support list](GameSupport.md)

## Installation
_**Recommended to use OptiScaler 0.7.8 or above**_
* Create a `plugins` folder where Opti is installed and put `OptiPatcher.asi` in this folder.  
* Enable ASI loading from `OptiScaler.ini`

```ini
LoadAsiPlugins=true
```
<img width="1246" height="250" alt="Untitled" src="https://github.com/user-attachments/assets/08fa4617-50ab-4837-a6c5-a8bda365abb5" />


**Warning** We have double checked patch patterns, but crashes might occur.

## Example of properly applied patch
* With OptiScaler **0.7.9 and newer**, when OptiPatcher applies properly, the game title will have an **(OP)** mention and **Spoof** will say **OFF**
  * _Opti 0.7.8 won't have the OP part in the title, but Spoof will still be OFF_

![OptiPatcher](https://github.com/user-attachments/assets/ecb581fe-3aa2-4e10-a21b-af9c973f1ba7)

