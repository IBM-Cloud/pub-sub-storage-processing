# Asynchronous data processing using object storage and pub/sub messaging

_This tutorial has been archived. The last version can be found [here](https://github.com/ibm-cloud-docs/solution-tutorials/blob/379011e5c4237a83d5f46132b6ff089b27258124/pub-sub-object-storage.md)_

This sample application uses an Apache Kafka based messaging service to orchestrate long running workloads to applications running in a Kubernetes cluster. This pattern is used to decouple your application allowing greater control over scaling and performance. Event Streams can be used to queue up the work to be done without impacting the producer applications, making it an ideal system for long-running tasks.

## License

See [License.txt](License.txt) for license information.
