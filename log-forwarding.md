# Mesos tasks log to Kibana/Splunk/log forwarders

When tasks log to stdout/stderr, Mesos writes the output to files inside the sandbox directory. It is desirable for tasks to log to stdout/stderr (according to the 12-factor app principles) and let the underlying infrastructure take care of the rest. Mesos agents sometimes run on machines with poor disk performance, and it's not desirable to write the logs to disk. This lets us configure Mesos so that it forwards logs instead.

## Team

- @eirslett
- @bahamat
- @andrewh1978

## Source

All source material is in https://github.com/eirslett/mesos/tree/feature/task-output-to-log-forwarder

## Documentation

Build Mesos from scratch with the patch applied, run Logstash with a TCP listener on localhost port 514, and run tasks.

## License

This material is licensed under the terms of the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
