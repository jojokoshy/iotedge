# iotedge
**Clear docker logs**



echo "" > $(docker inspect --format='{{.LogPath}}' <container_name_or_id>)

echo "" > $(docker inspect --format='{{.LogPath}}' edgeAgent)
