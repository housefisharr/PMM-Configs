# python ./config/rcm/rcm.py ./config/rcm -f -e
# python ./config/chazlarson/reset-posters.py
# PMM-Configs

Scripts to create Plex Collections
posters taken from zluckytraveler, overlays from bradmartin

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