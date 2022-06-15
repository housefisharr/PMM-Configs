
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

### [RhinoRhys](https://github.com/RhinoRhys/radarr-collections)'s Radarr Collections
- Switches: -f for full scan, -e to exclude movies in radarr's exclusion lists
- Run git clone while in the PMM appdata folder, for Unraid this is /mnt/user/appdata/plex-meta-manager, for me this is /opt/pmm
```bash
sudo git clone https://github.com/RhinoRhys/radarr-collections
docker exec -it pmm sh
python ./config/radarr-collections/rcm.py ./config/radarr-collections -f -e
```

### [ChazLarson](https://github.com/chazlarson/Media-Scripts)'s Reset Posters
- Resets all posters everywhere to Plex defaults
- Run git clone while in the PMM appdata folder, for Unraid this is /mnt/user/appdata/plex-meta-manager, for me this is /opt/pmm
```bash
sudo git clone https://github.com/chazlarson/Media-Scripts
docker exec -it pmm sh
python ./config/Media-Scripts/reset-posters.py
```
