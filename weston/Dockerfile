FROM alpine:latest

RUN apk add --no-cache weston weston-shell-fullscreen weston-backend-drm mesa-dri-intel mesa-gl xkeyboard-config

ENTRYPOINT ["weston-launch"]
