---
layout: page
title: Data
permalink: /Data/
---




What are the data we are making available via this server?  The following data tables are hosted here:

1) Phoenix_RT: Real-time data from Oct. 2017 to today, please see more details at the [Open Event Data Alliance](http://openeventdata.org/).

2) ICEWS: [Integrated Crisis Early Warning System from Harvard Dataverse](https://dataverse.harvard.edu/dataverse/icews) from 1995 to Sep. 2016.

3) Phoenix NYT: accumulated from 1945 to 2005, information about these [Phoenix Event Data are found at the Cline Center](https://clinecenter.illinois.edu/project/machine-generated-event-data-projects/phoenix-data).

4) Phoenix FBIS: accumulated from 1995 to 2004, information about these [Phoenix Event Data are found at the Cline Center](https://clinecenter.illinois.edu/project/machine-generated-event-data-projects/phoenix-data).

5) Phoenix SWB: accumulated from 1979 to 2015, information about these [Phoenix Event Data are found at the Cline Center](https://clinecenter.illinois.edu/project/machine-generated-event-data-projects/phoenix-data).

6) TERRIER: accumulated from 1979 to 2015, information about these [Temporally Extended, Regular, Reproducible International Event Records are found at OSF Home](https://osf.io/4m2u7/).

To access the real-time and historical event data on our server you need to first get an API key. You can go to this page to [sign up for an API key](http://149.165.156.33:5002/signup). Once you fill out the form, an API key will be sent to your email address.

Once you have the API key you can see how to format queries to the eventdata.utdallas.edu server [here](https://github.com/Sayeedsalam/spec-event-data-server).

The default return for the data fields is JSON.

Alternatively, we have built an [interactive site using Two Ravens](http://eventdata.2ravens.org/) to access the data.

In addition, we have an [R package and examples](https://github.com/KateHyoung/UTDEventData) avaiable.  The R package allows you to input your API key and then use some custom functions to return the results in an R dataframe.
