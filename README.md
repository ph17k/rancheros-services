# rancheros-services

## plex
```
docker run \
-d \
--name plex \
--network=host \
-e TZ="	Europe/Zurich" \
-e PLEX_CLAIM="claim-hmm_43sPtPjyvfpAcrox" \
-v plex-config:/config \
-v plex-temp:/transcode \
-v /mnt/data/media:/data \
plexinc/pms-docker
```
