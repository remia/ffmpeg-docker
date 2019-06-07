# ffmpeg-docker

A docker image for Cinema JPEG2000 decoding.

This uses image from https://github.com/jrottenberg/ffmpeg with two modifications :
*  Uses lastest version of OpenJPEG (threading improvements)
*  Correctly interpret cinema profiles as XYZ instead of RGB

Available on dockerhub : [ffmpeg](https://cloud.docker.com/u/remiaa/repository/docker/remiaa/ffmpeg)