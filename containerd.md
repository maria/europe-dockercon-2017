# ContainerD

- Container cli, grpc and protobuf
- Cli is beta
- Oci image support, runtime spec support, push and pull, namespace management
- Ctr the name of the cli
- Used in moby and kubernetes
- Moby contains containerd, docker engine, runc, swarmkit hyperkit, linuxkit(pluggable)
- He run docker as a container inside a containerd, in which he ran a redis container
- Kubelet talks with cri shim via protobuf
