# SDWUI LA-Z
This is a docker image of AUTOMATIC1111/stable-diffusion-webui by a lazy person.

It's tailored for Truenas Scale/Truecharts Custom App, but you can do whatever I guess.

Only NVIDIA/CPU.

You'll need to mount /app/tmp, (as emptyDir?) /app/extensions, (prolly as PVC), /app/configs(or not?), /app/models, /app/outputs, /app/results (prolly as Host Path or NFS share) on SCALE.
You'll might need some more down the line, because stable-diffusion-webui (and addons) is VERY immutable FS unfriendly.