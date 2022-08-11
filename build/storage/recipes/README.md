# Supported recipes
Currently, the following scenarios are represented:

* [hot-plug](./hot-plug.md) - describes how to deploy containers between
different machines and demonstrates virtio-blk hot-plug to a running host.
* [fio](./fio.md) - extends `hot-plug` scenario and describes how to run
fio traffic by means of `host-target` container through a hot-plugged virtio-blk
device.
* [scale-out](./scale-out.md) - similar to hot-plug recipe but describing
how to hot-plug/hot-unplug 64 virtio-blk devices.

In all cases host target platform is implied as KVM.

The picture below demonstrates the configuration exercised in these recipes
![System configuration for recipes](./system_configuration.png "System configuration for recipes")
