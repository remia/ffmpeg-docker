# ffmpeg-docker

A docker image for Cinema JPEG2000 deocding.

This uses image from https://github.com/jrottenberg/ffmpeg with two modifications :
*  Uses lastest version of OpenJPEG (threading improvements)
*  Correctly interpret cinema profiles as XYZ instead of RGB