# Mesos on Triton

Question: can we bring together Mesos' outstanding application scheduling capabilities with [Triton](http://joyent.com/triton)'s container-native infrastructure automation? Yes!

Mesos on Triton runs tasks in containers across multi-tenant bare metal, eliminating the need to configure hosts or pay for VMs that sit idle. This consumption model pricing lowers the barriers to running massively parallel tasks by lowering costs and complexity. Each task is run on bare metal in Triton's secure Docker containers.

Additionally, Mesos on Triton offers:

1. Network virtualization into every container: one or more unique IPs for every container, convenient for microservices
1. Strong isolation between containers: solves security problems and allows multi-tenant use
1. Bare metal performance
1. Hybrid cloud: [on premises](https://www.joyent.com/private-cloud) and in [Joyent's public cloud](https://www.joyent.com/public-cloud)
1. Hybrid workloads: Mesos and [non-Mesos](https://docs.joyent.com/public-cloud/instances) on the same hardware

## Team

- @blakeolsen
- @misterbisson

## Source

All source material is in the following locations:

- Changes to Mesos to support Triton are in https://github.com/joyent/mesos/pull/1 and https://github.com/joyent/mesos/pull/3
- Docker files and sample applications are in https://github.com/joyent/mesos-dockerfiles

## Documentation

Documentation is in https://github.com/joyent/mesos-dockerfiles

## License

This material is licensed under the terms of the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
