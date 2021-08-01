1) **Delete all images in one go :**
docker rmi $(docker images -a -q)

2) **Delete specific images : **
docker rmi <ImageId> <ImageId> ...
