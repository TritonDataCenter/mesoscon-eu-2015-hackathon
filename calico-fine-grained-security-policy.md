# Fine grained security policy with Calico.

The existing calico networking plugin for mesos already provides coarse grained security policy whereby tasks can
be grouped and isolated from tasks in other groups, e.g. so that your test apps can not modify your production data
stores! (see the video of the Calico presentation/demo on the Thursday of MesosCon Dublin 2015).

Our hack was extending this to allow more fine grained controls, with which you can open up/close specific IPs and 
ports to individual tasks within those groups.

## Team

- @neiljerram
- @emmagordon
- @lxpollitt
- @patclaffey

## Source

All source material is in https://github.com/projectcalico/calico-mesos/tree/njhack

## Documentation

Documentation does not exist yet - sorry! See the video of the hackathon presentations for a demo of the UI.

## License

This material is licensed under the terms of the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
