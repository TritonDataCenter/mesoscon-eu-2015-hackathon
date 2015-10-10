# Support for Multiple Disks in Mesos Agents

Although Mesos recently added persistent volumes, they don’t serve the needs of performance-critical databases. Because the persistent volumes only support sharing a single disk, it’s not possible to understand the performance of the disk or what the speed or contention with other tasks will be. Multiple disk support will allow for disk IO intensive applications to achieve reliable, high performance.

Built by @jmlvanre, @dgrnbrg, and @mpark

See the code at https://github.com/jmlvanre/mesos/tree/mesoscon-eu-multiple-disk

See the design docs at https://docs.google.com/document/d/1syPxygVNEHjG6FoyqslnpUGgNpYKU9QzKBuV2yKmjfQ/edit?ts=561796a7#

This is Apache licensed!
