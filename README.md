# Capstone Project DA11
## _Outdoor Recreation GDP and The National Parks_


# Table of Contents

- [Table of Contents](#table-of-contents)
- [Motivation](#motivation)
- [Technology](#technology)
- [Data](#data)
- [Analysis](#analysis)
- [Dashboard](#dashboard)

# Motivation
[(Back to top)](#table-of-contents)

Growing up, my mother and father were always deeply connected to nature. Our childhood summers were spent in the mountains hiking in North Carolina and our weekends were spent exploring the National and State parks in our backyard in Florida. As an adult, these experiences have made me a kayak loving, mountain hiking, exploration driven lady. 

During the Covid pandemic in 2020, it was exciting to watch as others throughout the nation seem to become more interested and invested in wandering the outdoors. This led me to wonder, as we entered into the new normal following the pandemic, did the interest in outdoor recreation continue? Was there ever really a sudden increase due to the pandemic? And is there a correlation between the interest and investment in outdoor recreation and National Park popularity or proximity?


# Technology
[(Back to top)](#table-of-contents)

- Tableau
- Python
- Excel
- Pandas
- Seaborn

# Data
[(Back to top)](#table-of-contents)

Data used for this project was gathered from multiple sources.

- Outdoor Recreation Satellite Account, U.S. and States, 2022:
https://www.bea.gov/data/special-topics/outdoor-recreation

- Outdoor Recreation Satellite Account, U.S. and States: State CSV files, 2012-2021 https://apps.bea.gov/regional/histdata/releases/1122orsa/index.cfm

- Visitation by State and by Park for Calendar Years 2017-2022: https://irma.nps.gov/Stats/SSRSReports/National%20Reports/Visitation%20By%20State%20and%20By%20Park%20(2017%20-%20Last%20Calendar%20Year)

- Divisional Average Temperature for 2022 with Supporting Historical Temperatures: https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/divisional/mapping/110/tavg/202212/12/value

# Analysis
[(Back to top)](#table-of-contents)

During the pandemic in 2020 we can see a significant drop which at first jumped out to me during my exploration because my original thought was “but so many people were diving deep into outdoor recreation during this time”. But it's important to keep in mind that during 2020, not only were a lot of government owned parks and services closed down during this time, but also we were seeing a major issue with supply chains. Purchases of recreation items like bicycles and RVs were significantly lower because weren’t really any to buy during this time. In 2021 we start seeing an upward trend comeback. Then in 2022, we have what appears to be a jump. With a closer look we see that it isn’t a sudden spike, it’s actually a comeback to the original growth trend that we had been seeing in the years prior to the pandemic.

When comparing the total outdoor recreation GDP with the visits per National Park owned properties, we can see that our most popular states don’t necessarily bring in the most GDP. Which with my analysis shows that those who wander may not be lost, they may just be enjoying more of the free resources in states they find beauty in; not states that have the goal of profiting off our their outdoor recreation interest.

# Dashboard

[(Back to top)](#table-of-contents)

Tableau Public Dashboard: 
<div class='tableauPlaceholder' id='viz1719372354188' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ou&#47;OutdoorRecGDP_NtlParks&#47;DB_20222&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='OutdoorRecGDP_NtlParks&#47;DB_20222' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ou&#47;OutdoorRecGDP_NtlParks&#47;DB_20222&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1719372354188');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1366px';vizElement.style.height='795px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1366px';vizElement.style.height='795px';} else { vizElement.style.width='100%';vizElement.style.height='827px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
 
```