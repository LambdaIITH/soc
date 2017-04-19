[Prometheus](https://github.com/prometheus) is an open-source systems monitoring and alerting toolkit originally built at SoundCloud. Since its inception in 2012, many companies and organizations have adopted Prometheus, and the project has a very active developer and user community. It is now a standalone open source project and maintained independently of any company.  

One of the most important things when using Prometheus is making sure that one's alerting expressions are correct (semantically, syntactically, and referring to existing template variables). It would be great to be able to assist the user with that.

This would be both frontend and backend / tooling work:  

- [Add UI for testing full alerting expressions over time](https://github.com/prometheus/prometheus/issues/1154)
- [General purpose rule/alert testing tool](https://github.com/prometheus/prometheus/issues/1695) 
- [Preview alerts in expression browser](https://github.com/prometheus/prometheus/issues/1220)
- [Alerts page should display expanded annotations](https://github.com/prometheus/prometheus/issues/1219)

...and more.