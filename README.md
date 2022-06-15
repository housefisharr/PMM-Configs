
## Scripts to create Plex Collections with [PMM](https://github.com/meisnate12/Plex-Meta-Manager)
### Usage & info

Things to keep in mind: 
- Run git clone while in the PMM appdata folder, for Unraid this is /mnt/user/appdata/plex-meta-manager, for me this is /opt/pmm
```bash
sudo git clone https://github.com/housefisharr/PMM-Configs
sudo mv config.yml config-old.yml
sudo cp ./PMM-Configs/config.yml ./config.yml
docker exec -it pmm sh
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
