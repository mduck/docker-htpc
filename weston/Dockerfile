FROM alpine:latest

RUN apk add --no-cache weston weston-clients weston-shell-fullscreen weston-backend-drm mesa-dri-intel mesa-gl

COPY xdg_runtime_dir /etc/profile.d/xdg_runtime_dir

ENTRYPOINT ["weston-launch"]
