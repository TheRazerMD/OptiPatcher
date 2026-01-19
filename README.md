# OptiPatcher
An **ASI Plugin for OptiScaler** for exposing DLSS/DLSS-FG inputs without spoofing in **supported games**.  

> [!NOTE]
> * **For AMD and Intel users!**
> * _Helps Intel Arc users a lot because newer versions of Unreal Engine have issues with spoofing, causing `D3D12 not supported` errors._
> * **OptiPatcher helps avoid performance overhead or crashes/artifacts caused by Dxgi spoofing!**

## Currently supported games
* Check the [Game Support list](GameSupport.md)

## Installation
_**Recommended to use OptiScaler 0.7.8 or above**_
* Create a `plugins` folder where Opti is installed and put `OptiPatcher.asi` in this folder.  
* Enable ASI loading from `OptiScaler.ini`

```ini
LoadAsiPlugins=true
```

<img width="1237" height="294" alt="pluginsmerged" src="https://github.com/user-attachments/assets/08206326-3ba8-4a8d-928f-b1c29dcd9f19" />
<img width="744" height="181" alt="loadasiplugins" src="https://github.com/user-attachments/assets/79003cee-7238-4be0-b47e-55f16123e53c" />

**Warning** We have double checked patch patterns, but crashes might occur.

## Example of properly applied patch
* With OptiScaler **0.7.9 and newer**, when OptiPatcher applies properly, the game title will have an **(OP)** mention and **Spoof** will say **OFF**
  * _Opti 0.7.8 won't have the OP part in the title, but Spoof will still be OFF_

![OptiPatcher](https://github.com/user-attachments/assets/ecb581fe-3aa2-4e10-a21b-af9c973f1ba7)

