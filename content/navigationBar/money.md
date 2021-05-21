---
draft: false
---

<br>
<br>

## Money Transaction

Since GAS tech has collected geospatial data from the vehicles they have assigned to their employees, we use Tableau to graph the driving routes of each vehicle and fix those routes on the map of Kronos to tell which ID has abnormal travel behaviors. From the animations on our website, we can tell the locations travelled by each vehicle. We graph the travelling routes in the color of blue and the visiting frequency is demonstrated by the degree of color saturation. We can successfully track information about drivers who drive Vehicles ID 1-35, since those are assigned to employees as a welfare of GAStech company, and those are company properties whereas car ID in the form of 100 or something cannot be traced. Every employee has a possibility to request driving those trunks to pertain to business.

By comparing the gps data and the transaction data, we matched some of the cards with the car id. We hypothesized that the large amount of expense was made by truck drivers for business transactions.

We also identified car 35 that frequently travelled to Kronos Capitol during the night, with the corresponding employee being Vasco-Pais who has a close relationship with government officials.

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://kind-lewin-43c0b6.netlify.app/" height="400" width="650"></iframe>

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://eager-heisenberg-88142b.netlify.app/" height="400" width="650"></iframe>

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://priceless-mclean-cd4e2d.netlify.app/" height="400" width="650"></iframe>

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://sad-heisenberg-0378e1.netlify.app/" height="400" width="650"></iframe>

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://relaxed-shirley-a0d74f.netlify.app/" height="400" width="650"></iframe>

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://unruffled-hodgkin-df4004.netlify.app/" height="400" width="650"></iframe>

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://serene-kowalevski-bdd70a.netlify.app/" height="400" width="650"></iframe>

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://vigorous-lalande-66a6b2.netlify.app/" height="400" width="650"></iframe>

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://objective-khorana-9996fb.netlify.app/" height="400" width="650"></iframe>

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://priceless-hermann-5dec8e.netlify.app/" height="400" width="650"></iframe>

For the graphs of the credit and loyalty card transactions, we decided to use bar graphs as it doesn’t indicate an idea of consistency, which the line graphs do, and still have a good view of the linear timeline, unlike the scatterplots that look all jumbled together.

In analyzing the most popular locations and when they are popular, we filter out according to the amount of purchasement each credit card generates by selecting those credit card IDs which surpasses other IDs by a standard deviation. In this way, we sorted out 11 locations. We first graphed those using line charts and we could clearly identify locations with a very high amount of purchasement from our visualization. For instance, Guy’s gyros show several distinct fluctuations. Then, we switched our visualization to bar charts to better demonstrate the amount of purchasement. Some of the locations have extremely high amounts of purchasement particular dates. We raised a hypothesis that the amount of purchasement has an association with the amount of people visited. Regardless, we cannot tell from the graph which date Hippokampos has the highest amount of purchasement.

Then, we attempt to look at the purchasement activities of each credit card. Normally, each credit card makes purchasement at 3 or 4 locations; however, we find several credit card IDs which can be categorized as anomalies, being credit card numbers 9551, 2276 and 9220. Among those, 9551 have made purchases on 5 various locations with a total amount exceeding 10000 on January 13th. In addition, credit card 9551 has made extremely more purchases compared to other IDs while the graph demonstrates that its purchasement activity has fractures. On some days, 9551 makes an excessive amount of purchases while on other occasions, the amount of purchases is pretty low. The transactions of 2276 were also pretty interesting. We would expect that the more places you go, the more money you would spend that day. However, 2276 had lower purchases on days when it went to more places as opposed to what we would expect.

With our analysis of the loyalty card activity, we find several anomalies in their purchasing activities, like L8062 and L4049 all have suspicious activities on 16th or 18th. L8477 has similar activity with another loyalty card.

As we found those suspicious activities indeed exist and those anomalies of credit card and the loyalty card have connections, we try to further our investigation by adding the vehicle data to my analysis of the credit card and the loyalty card data to search for clues in explaining those anomalies.

<br>
<br>

<div class='tableauPlaceholder' id='viz1621612534558' style='position: relative'><noscript><a href='#'><img alt='Comparison of Location&#39;s Count and Price ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MC&#47;MC2_cc_loyal&#47;Sheet3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MC2_cc_loyal&#47;Sheet3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MC&#47;MC2_cc_loyal&#47;Sheet3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1621612534558');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

<br>
<br>

The data used for this graph is cc_data. Price is indicated by the color. The darker the color, the more price is spent in this location.  cc card visit count is indicated by the size. The larger the size, the more card number has been used in this location. Tooltip is applied in this figure so the user can check specific prices and count numbers.

<br>
<br>

<div class='tableauPlaceholder' id='viz1621612831263' style='position: relative'><noscript><a href='#'><img alt='Loyalty: comparison of each location&#39;s price and loyalty card visit ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;54&#47;54Q6X7NCD&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;54Q6X7NCD' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;54&#47;54Q6X7NCD&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1621612831263');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

<br>
<br>

Similar to the last graph, but the data set used here is loyalty_data.

<br>
<br>

<div class='tableauPlaceholder' id='viz1621612659509' style='position: relative'><noscript><a href='#'><img alt='CC Cards&#39;s Total Price Change by Day ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MC&#47;MC2_cc_loyal&#47;Sheet6&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MC2_cc_loyal&#47;Sheet6' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MC&#47;MC2_cc_loyal&#47;Sheet6&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1621612659509');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

<br>
<br>

<div class='tableauPlaceholder' id='viz1621612684781' style='position: relative'><noscript><a href='#'><img alt='Loyalty&#39;s Total Price Change by Day ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MC&#47;MC2_cc_loyal&#47;Sheet8&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MC2_cc_loyal&#47;Sheet8' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MC&#47;MC2_cc_loyal&#47;Sheet8&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1621612684781');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

<br>
<br>

Total price change of Loyalty card and credit card from January 5 to January 20. The line chart can better reveal the trend across time. Noticeably, on January 15, the trend of loyalty cards abruptly increased, yet for credit cards, it decreased  on January 16.

<div class='tableauPlaceholder' id='viz1621612896532' style='position: relative'><noscript><a href='#'><img alt='CC: Each Location&#39;s Total Visit Count ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MC&#47;MC2_cc_loyal&#47;Sheet9&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MC2_cc_loyal&#47;Sheet9' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MC&#47;MC2_cc_loyal&#47;Sheet9&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1621612896532');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

<br>
<br>

Total visit count by card number of each location from January 5 to January 20.

<br>
<br>

<div class='tableauPlaceholder' id='viz1621612936679' style='position: relative'><noscript><a href='#'><img alt='Loyalty: Each Location&#39;s Total Visit Count ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MC&#47;MC2_cc_loyal&#47;Sheet10&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MC2_cc_loyal&#47;Sheet10' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MC&#47;MC2_cc_loyal&#47;Sheet10&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1621612936679');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

Total visit count by loyalty number of each location from January 5 to January 20.

<br>
<br>

<div class='tableauPlaceholder' id='viz1621612973368' style='position: relative'><noscript><a href='#'><img alt='CC: Carlyle Chemical Inc. Price Change by Day ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MC&#47;MC2_cc_loyal&#47;Sheet11&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MC2_cc_loyal&#47;Sheet11' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MC&#47;MC2_cc_loyal&#47;Sheet11&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1621612973368');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

<br>
<br>

<div class='tableauPlaceholder' id='viz1621612992501' style='position: relative'><noscript><a href='#'><img alt='Loyalty: Carlyle Chemical Inc. Price Change by Day ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MC&#47;MC2_cc_loyal&#47;Sheet12&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MC2_cc_loyal&#47;Sheet12' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MC&#47;MC2_cc_loyal&#47;Sheet12&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1621612992501');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

Based on former analysis, we think Carlyle Chemical Inc. transaction is quite suspicious so we further look into how the trend varied using credit card usage count and loyalty usage count.

<br>
<br>
<br>
<br>

<hr style="border:0.5px dashed black"> </hr>
