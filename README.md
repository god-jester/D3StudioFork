# D3StudioFork v4.1 by jester
A heavily improved Diablo 3 (RoS/Eternal) editor based on the recently open-sourced [D3Studio](https://github.com/Tonic-Box/D3Studio) by TonicBox

Downloads can be found under [Releases](https://github.com/god-jester/D3StudioFork/releases) 
<hr>

## Massively improved performance when opening saves, allowing for huge GBID lists

| Test System:<br>Ryzen 9 3950X CPU<br>64GB Memory | Light GBID Lists<br><br>App Start Time | Light GBID Lists<br><br>Open 16-Hero Save |  | Full GBID Lists<br><br>App Start Time | Full GBID Lists<br><br>Open 16-Hero Save |
|---|:---:|:---:|:---:|:---:|:---:|
| [D3StudioFork v4](https://github.com/god-jester/D3StudioFork/releases/latest)<br>[D3StudioFast](https://github.com/god-jester/D3StudioFast/releases/latest) | **_1.2 seconds_** | **_13 seconds_** |  | **_2.8 seconds_** | _**17 seconds**_ |
| [D3Studio v3.5](https://github.com/Tonic-Box/D3Studio/releases/tag/v3.5) | 3.3 seconds | 1 min 21 seconds |  | 41 seconds | 4 mins 1 second |
| [IITheDevilsSonII Fork v5.4](https://github.com/xXTheDevilsSonXx/D3Studio/releases/tag/5.4) <ins>³</ins> | 4.7 seconds | 1 min 31 seconds |  | 44 seconds | 4 mins 27 seconds |


## Massively improved memory usage and fixed memory leaks when opening multiple saves

| Test System:<br>Ryzen 9 3950X CPU<br>64GB Memory | <ins>EXE Size</ins><br><br><br> | <ins>App Started</ins><br><br>Memory Used | <ins>Open 16-Hero Save</ins><br><br>Memory Used | <ins>Open 16-Hero Save Twice</ins><br><br>Memory Used |
|---|:---:|:---:|:---:|:---:|
| [D3StudioFork v4](https://github.com/god-jester/D3StudioFork/releases/latest) | **_3.29 MB_** | **_44.1 MB_** | **_109 MB_** | **_113 MB_** |
| [D3StudioFast](https://github.com/god-jester/D3StudioFast/releases/latest) | 6.87 MB | 64.2 MB | 654 MB | **661 MB** |
| [D3Studio v3.5](https://github.com/Tonic-Box/D3Studio/releases/tag/v3.5) | 6.64 MB | 48.3 MB | 599 MB | **1,129 MB** |
| [IITheDevilsSonII Fork v5.4](https://github.com/xXTheDevilsSonXx/D3Studio/releases/tag/5.4) <ins>³</ins> | 7.37 MB | 110 MB | 781 MB | **1,340 MB** |

<ins>³</ins> Yes, this was tested again with latest version "v5.4" and 2.7.3 GBID lists

<hr>

![image](https://i.imgur.com/f6bp7iC.png)

![image](https://i.imgur.com/LHBHCJX.png)


Demo video:


https://user-images.githubusercontent.com/90997402/149216231-26232c89-eb1e-4837-a62c-bb3995de7af5.mp4

![image](https://i.imgur.com/kh3aRXu.png)

![image](https://i.imgur.com/s3xNnnp.png)
