This is the top-level project for HttpComponents.

The POM currently references the following modules:

../httpcore
../httpclient

which must be in the relevant directories.

The site.xml  file assumes that module documentation is located as follows:

Component          Directory relation to TLP (i.e. http://hc.apache.org/)
=========          =========================
HttpClient         httpcomponents-client-ga (link)
HttpCore           httpcomponents-core-ga (link)
HttpAsyncClient    httpcomponents-asyncclient-dev (link)
Commons HttpClient httpclient-legacy

The entries tagged with "(link)" are soft links to the actual directory, for example:

httpcomponents-client-ga -> httpcomponents-client-4.1.0