## LinuxKit

Slides: https://www.slideshare.net/Docker/linuxkit-deep-dive

## Notes

- Moby - toolkit for building system images, on top of containerd
- Kubernetes and Microsoft support

- Platform support - aws, azure, vmware and others
- Multi arch
- Flexible networking and wireguard
- Namespace sharing
- Persistent disk
- Build on linuxkit/alpine
- Has a mirror of alpine apk
- Multi stage builds (from scratch) - after we install all and then create a new image only with the files needed
- Custom network interface
