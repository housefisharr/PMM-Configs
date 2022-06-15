
## Scripts to create Plex Collections with [PMM](https://github.com/meisnate12/Plex-Meta-Manager)
### Usage & info

Things to keep in mind: 

- Run as Administrator 
- [PowerShell execution policies](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.security/set-executionpolicy?view=powershell-7.2) 

```shell
git clone https://github.com/SegoCode/DebloBat
cd DebloBat
Deblo.bat
```
### How to install
#### CD into PMM's persistent volume on docker host and run
```bash
sudo git clone https://github.com/housefisharr/PMM-Configs
```
### How to run
### PMM Default
```shell
python plex_meta_manager.py -r
```
### Radarr Collections
-f for full scan, -e to exclude movies in radarr's exclusion lists
https://github.com/RhinoRhys/radarr-collections
```shell
python ./config/rcm/rcm.py ./config/rcm -f -e
```
### ChazLarson's Reset Posters
Resets all posters everywhere to Plex defaults
https://github.com/chazlarson/Media-Scripts
#### How to install
##### CD into PMM's persistent volume on docker host and run
```bash
sudo git clone https://github.com/housefisharr/PMM-Configs
```
#### How to run
```shell
python ./config/chazlarson/reset-posters.py
```
