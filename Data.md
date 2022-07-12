---
layout: page
title: Data
permalink: /Data/
---




What are the data we are making available via this server? The following data tables are hosted here:

1) Phoenix_RT: Real-time data from October 2017 to today. Please see more details at the [Open Event Data Alliance](http://openeventdata.org/).

2) ICEWS: [Integrated Crisis Early Warning System from Harvard Dataverse](https://dataverse.harvard.edu/dataverse/icews) from January 1, 1995, to September 28, 2020.

3) Phoenix NYT: Accumulated from 1945 to 2005. Information about these [Phoenix Event Data are found at the Cline Center](https://clinecenter.illinois.edu/project/machine-generated-event-data-projects/phoenix-data).

4) Phoenix FBIS: Accumulated from 1995 to 2004. Information about these [Phoenix Event Data are found at the Cline Center](https://clinecenter.illinois.edu/project/machine-generated-event-data-projects/phoenix-data).

5) Phoenix SWB: Accumulated from 1979 to 2015. Information about these [Phoenix Event Data are found at the Cline Center](https://clinecenter.illinois.edu/project/machine-generated-event-data-projects/phoenix-data).

6) TERRIER: Accumulated from 1979 to 2015. Information about these [Temporally Extended, Regular, Reproducible International Event Records are found at OSF Home](https://osf.io/4m2u7/).

To access the real-time and historical event data on our server, you need to first get an API key. You can go to this page to [sign up for an API key](https://eventdata.utdallas.edu/signup). Once you fill out the form, an API key will be sent to your email address. Please check your spam and junk email if you do not receive the API key in your inbox.

Once you have the API key, you can see how to format queries to the eventdata.utdallas.edu server [here](https://github.com/Sayeedsalam/spec-event-data-server).

The default return for the data fields is JSON.

Alternatively, we have built an [interactive site using Two Ravens](http://eventdata.2ravens.org/) to access the data.

In addition, we have an [R package and examples](https://github.com/KateHyoung/UTDEventData) available. The R package allows you to input your API key and then use some custom functions to return the results in an R dataframe.
