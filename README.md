# awesome-google-cloud-operations
A collection of libraries, plugins, examples, documents et al for Google Cloud Operations (formaly known as "Stackdriver")

## Google Cloud Logging

### Documents

* [Cloud Logging documentation -- Google Cloud](https://cloud.google.com/logging/docs?hl=en)

### Client libraries

#### Official

* [Java](https://github.com/googleapis/java-logging)
* [Go](https://github.com/googleapis/google-cloud-go/tree/logging/v1.0.0/logging)
  * [pkg.go.dev - cloud.google.com/go/logging](https://pkg.go.dev/cloud.google.com/go/logging)
* [Python](https://github.com/googleapis/python-logging)
  * [PyPI - google-cloud-logging](https://pypi.org/project/google-cloud-logging/)
* [Node.js](https://github.com/googleapis/nodejs-logging)
  * [npm - @google-cloud/logging](https://www.npmjs.com/package/@google-cloud/logging)

#### Agents

* [GoogleCloudPlatform/google-fluentd](https://github.com/GoogleCloudPlatform/google-fluentd)


### Blogs

* [How to find--and use--your GKE logs with Cloud Logging](https://cloud.google.com/blog/products/management-tools/finding-your-gke-logs)
* [Tools for debugging apps on Google Kubernetes Engine](https://cloud.google.com/blog/products/containers-kubernetes/tools-for-debugging-apps-on-google-kubernetes-engine)
* [Using logging for your apps running on Kubernetes Engine](https://cloud.google.com/blog/products/management-tools/using-logging-your-apps-running-kubernetes-engine)



## Google Cloud Monitoring

### Documents/Blogs

* [Cloud Monitoring documentation -- Google Cloud](https://cloud.google.com/monitoring/docs/?hl=en)

### Client libraries

#### Official

* [Java](https://github.com/googleapis/java-monitoring)
  * [Javadoc](https://googleapis.dev/java/google-cloud-monitoring/latest/)
* [Go](https://github.com/googleapis/google-cloud-go/tree/master/monitoring/apiv3)
  * [pkg.go.dev - cloud.google.com/go/monitoring/apiv3](cloud.google.com/go/monitoring/apiv3)
* [Python](https://github.com/googleapis/python-monitoring)
  * [PyPI - google-cloud-monitoring](https://pypi.org/project/google-cloud-monitoring/)
* [Node.js](https://github.com/googleapis/nodejs-monitoring)
  * [npm - @google-cloud/monitoring](https://www.npmjs.com/package/@google-cloud/monitoring)

#### 3rd party

* [OpenCensus](https://opencensus.io/)
  * Java
    * [OpenCensus](https://github.com/census-instrumentation/opencensus-java)
      * [Javadoc - io.opencensus.stats](https://www.javadoc.io/doc/io.opencensus/opencensus-api/latest/index.html)
    * [OpenCensus Java exporter](https://github.com/census-instrumentation/opencensus-java/blob/master/exporters/stats/stackdriver/src/main/java/io/opencensus/exporter/stats/stackdriver/StackdriverStatsExporter.java)
      * [Javadoc - io.opencensus.exporter.stats.stackdriver.StackdriverStatsExporter](https://www.javadoc.io/doc/io.opencensus/opencensus-exporter-stats-stackdriver/latest/index.html)
  * Go
    * [OpenCensus](https://github.com/census-instrumentation/opencensus-go)
      * [pkg.go.dev - go.opencensus.io](https://pkg.go.dev/go.opencensus.io/)
    * [OpenCensus Go exporter](https://github.com/census-ecosystem/opencensus-go-exporter-stackdriver)
      * [pkg.go.dev - contrib.go.opencensus.io/exporter/stackdriver](https://pkg.go.dev/contrib.go.opencensus.io/exporter/stackdriver?tab=doc)
  * Python
    * [OpenCensus](https://github.com/census-instrumentation/opencensus-python)
      * [PyPI - opencensus](https://github.com/census-instrumentation/opencensus-python)
    * [OpenCensus Python exporter](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-stackdriver)
      * [PyPI - opencensus-ext-stackdriver](https://pypi.org/project/opencensus-ext-stackdriver/)
  * Node.js
    * [OpenCensus](https://github.com/census-instrumentation/opencensus-node)
      * [npm - @opencensus/nodejs](https://www.npmjs.com/package/@opencensus/nodejs)
    * [OpenCensus Node.js exporter](https://github.com/census-instrumentation/opencensus-node/tree/master/packages/opencensus-exporter-stackdriver)
      * [npm - @opencensus/exporter-stackdriver](https://www.npmjs.com/package/@opencensus/exporter-stackdriver)


### Plugins for other tools

* [mia-0032/fluent-plugin-stackdriver-monitoring](https://github.com/mia-0032/fluent-plugin-stackdriver-monitoring)


## Google Cloud Trace

### Documents

* [Cloud Trace documentation -- Google Cloud](https://cloud.google.com/trace/docs/?hl=en)

### Client libraries

#### Official

* [Java](https://github.com/googleapis/java-trace)
  * [Javadoc](https://googleapis.dev/java/google-cloud-trace/latest/)
* [Go](https://github.com/googleapis/google-cloud-go/tree/master/trace/apiv2)
  * [pkg.go.dev - cloud.google.com/go/trace/apiv2](cloud.google.com/go/trace/apiv2)
* [Python](https://github.com/googleapis/python-trace)
  * [PyPI - google-cloud-trace](https://pypi.org/project/google-cloud-trace/)
* [Node.js](https://github.com/googleapis/nodejs-monitoring)
  * [npm - @google-cloud/trace-agent](https://www.npmjs.com/package/@google-cloud/trace-agent)

#### 3rd party

* [OpenCensus](https://opencensus.io/)
  * Java
    * [OpenCensus](https://github.com/census-instrumentation/opencensus-java)
      * [Javadoc - io.opencensus.trace](https://www.javadoc.io/doc/io.opencensus/opencensus-api/latest/index.html)
    * [OpenCensus Java exporter](https://github.com/census-instrumentation/opencensus-java/blob/master/exporters/trace/stackdriver/src/main/java/io/opencensus/exporter/trace/stackdriver/StackdriverTraceExporter.java)
      * [Javadoc - io.opencensus.exporter.stats.stackdriver.StackdriverTraceExporter](https://www.javadoc.io/doc/io.opencensus/opencensus-exporter-trace-stackdriver/latest/index.html)
  * Go
    * [OpenCensus](https://github.com/census-instrumentation/opencensus-go)
      * [pkg.go.dev - go.opencensus.io](https://pkg.go.dev/go.opencensus.io/)
    * [OpenCensus Go exporter](https://github.com/census-ecosystem/opencensus-go-exporter-stackdriver)
      * [pkg.go.dev - contrib.go.opencensus.io/exporter/stackdriver](https://pkg.go.dev/contrib.go.opencensus.io/exporter/stackdriver?tab=doc)
  * Python
    * [OpenCensus](https://github.com/census-instrumentation/opencensus-python)
      * [PyPI - opencensus](https://github.com/census-instrumentation/opencensus-python)
    * [OpenCensus Python exporter](https://github.com/census-instrumentation/opencensus-python/tree/master/contrib/opencensus-ext-stackdriver)
      * [PyPI - opencensus-ext-stackdriver](https://pypi.org/project/opencensus-ext-stackdriver/)
  * Node.js
    * [OpenCensus](https://github.com/census-instrumentation/opencensus-node)
      * [npm - @opencensus/nodejs](https://www.npmjs.com/package/@opencensus/nodejs)
    * [OpenCensus Node.js exporter](https://github.com/census-instrumentation/opencensus-node/tree/master/packages/opencensus-exporter-stackdriver)
      * [npm - @opencensus/exporter-stackdriver](https://www.npmjs.com/package/@opencensus/exporter-stackdriver)

### Blogs

* [Viewing Stackdriver Trace spans and request logs in multi-project deployments](https://cloud.google.com/blog/products/gcp/viewing-trace-spans-and-request-logs-in-multi-project-deployments)


## Google Cloud Profiler

### Documents/Blogs

* [Cloud Profiler documentation -- Google Cloud](https://cloud.google.com/profiler/docs/about-profiler)

### Client libraries

#### Official

* [Java](https://github.com/GoogleCloudPlatform/cloud-profiler-java)
  * NOTE: this is Java agent, not application instrumentation library
* [Go](https://github.com/googleapis/google-cloud-go/tree/master/profiler)
  * [pkg.go.dev - cloud.google.com/go/profiler](cloud.google.com/go/profiler)
* [Python](https://github.com/GoogleCloudPlatform/cloud-profiler-python)
  * [PyPI - google-cloud-profiler](https://pypi.org/project/google-cloud-profiler)
* [Node.js](https://github.com/googleapis/cloud-profiler-nodejs)
  * [npm - @google-cloud/profiler](https://www.npmjs.com/package/@google-cloud/profiler)