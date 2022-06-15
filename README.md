
## Scripts to create Plex Collections
https://github.com/meisnate12/Plex-Meta-Manager
#### How to install
##### CD into PMM's persistent volume on docker host and run
```bash
sudo git clone https://github.com/housefisharr/PMM-Configs
```
## How to run
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
