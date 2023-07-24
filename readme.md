this is an example of me trying to get nginx working on rootless podman, using a compose file

    podman-compose up
    open http://localhost:11221

turns out nginxinc/nginx-unprivileged works better
