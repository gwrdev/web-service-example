# Web Service Demonstration

The original source for this was taken from an article: 

    https://examples.javacodegeeks.com/enterprise-java/apache-camel/apache-camel-cxf-example/

The example demonstrates how you can use Apache Camel, Spring Boot, CXF and OpenShift. It is also built in Dev Studio

The example can be built and run on OpenShift using a single goal:

    mvn fabric8:deploy

When the example runs in OpenShift, you can use the OpenShift client tool to inspect the status

To list all the running pods:

    oc get pods

Then find the name of the pod that runs this quickstart, and output the logs from the running pods with:

    oc logs <name of pod>


