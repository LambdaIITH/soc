[Prometheus](https://github.com/prometheus) is an open-source systems monitoring and alerting toolkit originally built at SoundCloud. Since its inception in 2012, many companies and organizations have adopted Prometheus, and the project has a very active developer and user community. It is now a standalone open source project and maintained independently of any company.  

Prometheus is not really excellent in the correctness/bug-free-ness department yet, partially because certain key components either lack tests or one would have to run them in a real-world scenario for a while to discover certain bugs.  

This end-result of this project is to have a test environment that runs a Prometheus release end-to-end (with different SD mechanisms) for a while and checks the results (evaluated expressions, alerts, etc.) for sanity.  

