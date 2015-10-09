# Mesos on ARM

Get mesos up and running on arm.

*Status:*

![It Compiles!](http://biobeasts.artix.com/content/images/2015/05/It_Compiles_Ship_It.png)

Beyond that we did not yet succeed in getting it running but have
identified issues and are working through them. We also got a small
ARM dev farm going on Scaleways but need to make better use of it.

Some things that will affect the wider mesos world will be the following:

- Upgrading zookeeper.
- Upgrading leveldb.

Possibly of less interest:

![C o m p i l i n g . . .](https://imgs.xkcd.com/comics/compiling.png)

- Documenting how to use [distcc](https://github.com/distcc/distcc)
  to speed up mesos builds.

## Team

- @lyda ([lyda](https://twitter.com/lyda) or kevin@ie.suberic.net if you want
  to ping me about helping)
- @janisz

## Source

All source material is on github in
[lyda/mesos-on-arm](https://github.com/lyda/mesos-on-arm).

## Documentation

Currently we're using the github
[tickets](https://github.com/lyda/mesos-on-arm/issues)
to track some initial ideas for projects that result from this as
well as some infrastructure issues we've come across.

There's also some draft docs living in
[this wiki](https://github.com/lyda/mesos-on-arm/wiki).

As we have something more mature to offer we'll be updating
[MESOS-2021](https://issues.apache.org/jira/browse/MESOS-2021).

## License

All of this will be contributed under the licenses of the relevant
projects. The bulk of it seems to be under the terms of the
[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
