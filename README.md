# PMM-Configs

Scripts to create Plex Collections
https://github.com/meisnate12/Plex-Meta-Manager

## How to run
### PMM Default
```shell
python plex_meta_manager.py -r
```
### Radarr Collections
-f for full scan, -e to exclude movies in radarr's exclusion lists
```shell
python ./config/rcm/rcm.py ./config/rcm -f -e
```
### ChazLarson's Reset Posters
Resets all posters everywhere to Plex defaults
```shell
python ./config/chazlarson/reset-posters.py
```