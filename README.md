# hexoblog
Docker stuff for a Hexo blog

This should be used together with docker-compose.

Create the volume folder and run:
mkdir blog
docker-compose -d up

If docker volumes are being used, when running for the first time one needs to run hexo init again for creating the files in the new volume.
