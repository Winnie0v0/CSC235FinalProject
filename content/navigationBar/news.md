---
draft: false
lightgallery: true
---

<br>
<br>

## Time Line

The news report directory consists of 874 current and historical news reports from multiple domestic and translated foreign sources in text file format.

To identify and extract subjective information in source materials, we conducted a sentiment analysis. Specifically, we adopted a "semi-supervised learning," in the process of which we first trained a model using a labeled dataset available online, and then applied the model to the news data for sentiment classification.

Since all the labeled news-related data we found was either at sentence-level or using a different set of labels like "true" and "fake," we worked around by using a movie dataset created by Cornell University. The dataset contains 1000 positive and 1000 negative processed reviews on movies. Fortunately, movie reviews and news reports are similar because both are a mixture of quotes, descriptions, and opinions. After training using this polarity dataset, we obtained the sentiment labels by applying the model to the news data and used the results to create the word clouds. Happily, we found the sentiment classification to be reasonably successful.

<br>
<br>

{{< image src="/images/positive.png" alt="Wordcloud of positive news reports" caption="Positive" height="50%" width="50%">}}

{{< image src="/images/negative.png" alt="Wordcloud of negative news reports" caption="Negative" height="50%" width="50%">}}

<br>
<br>

For the negative cloud, "January Update" and "employee" appear hugely because the kidnapping of several employees of GAStech happened in January 2014. "Elodis" is a rural township outside of the capital Abila where people believe the water is contaminated by the GAStech International. The Protectors of Kronos was also founded in 1998 in Elodis, which we confirmed to be the group that was in charge of the kidnapping.

In the positive cloud, we were able to recognize several names. Sten Sanjorge, Sr. is the founder of International GAStech. Later, his son Sten Sanjorge, Jr. became the president and CEO of GAStech. A handful of news reports, especially those published in the earlier years, have positively recorded the events of GAStech. When Sanjore condemned POK as terrorists, he demanded that the government of the system of Kronos should assure "not only the security of my employees but all the citizens of Kronos" (The Light of Truth). As to the opening of the new offices of GAStech, it wrote that "the commission of Sanjorge to Kronos shows a prosperous future for all"(The Guide). In addition to the Sanjorge, "Elian Karel" is also a high-frequency name. Karel was a former POK leader who died in 2009, many reports served to remember Karel, and the anniversary of Karel's death takes place on June 19 every year after that.

As we read through the news articles, we identified that Petrus Gerhard and Maha Salo seemed to be journalists the were affiliated with the POK, and by reading through the news of Petrus Gerhard, we began to piece together the timeline of how POK became so radical and why it led to the kidnapping event, along with why Elodis was so big on the negative word count. In 1998, POK was still a group of environmentalists and activists that were concerned with the water contamination that was happening in the town of Elodis. The gas drilling operation from GasTech was contaminating the water supply with various types of toxic chemicals, resulting in various illnesses in the people of Elodis and the death of Juliana Vann, who died from cancer induced by benzene in the water. POK began protesting for clean water, human rights, and against the corruption of the Government of Kronos and GAStech International, asking the government to do something, but to no avail. In 2009/ 03/12, Elian Karel, leader of POK, was arrested for tax evasion, though the real reason was probably because he was getting on the government’s nerves and angered the president by sending him two bottles of the poisonous water for the president’s birthday. He was never released, as he later died from what the officials say was a heart attack, but the POK and it’s supporters suspect to be murder as Elian’s body had signs of “blunt force trauma, abrasions and lacerations.” From that point forward, Petrus’ news began to become more cynical, although he was still focused on trying to get justice for Elodis, Elian, and Juliana from the government, which is embodied in his recount of seeming to hear voices telling him to "Remember Juliana! Remember Elian!" After 2012/06/19, which is the day where people of the POK had gathered to remember Elian but was chased away by the police by batons and pepper spray, Petrus’ news began to become much more cynical and began cooperating with Maha Salo on publishing news in Homeland Illumination, and by 2014/01/21 Maha Salo published an article (that looked crazy with all caps) that claiming responsibility and celebrating the abductions that happened on 2014/01/20.

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://news-semtiments.netlify.app" height="400" width="100%"></iframe>

<br>

As the story unfolds, we realized that not all sources are neutral and objective. Some sources leaned towards POK. They are:

* Homeland Illumination  (Main Journalists: Petrus Gerhard, Maha Salo)
* News Online Today（The first report was published by Petrus Gerhard in March, 1998）
* All news today  (One published by report Petrus Gerhard in 1998)
* Centrum Sentinel（Petrus Gerhard published one report on January 21, 2014)(weird!)

<br>

What they all have in common is that they all seem to be under the control of Petrus Gerhard. And they regularly post articles to remember the death of Karel. From January 19th to 21st, they all kept reporting events in forms that looked like primary sources, but we did not find any clues showing they actually sent any writers to the site. Looking at the count plot, News Online Today seems to be the most active source, which corresponds to the fact that it was started in 1998.

The following are sources that we believe to be primary sources:

* The Abila Post (sent Haneson Ngohebo, writer of the On the Scene Blog, to live blog the event, January 20-21, 2014)
* Modern Rubicon (sent a writer, January 20-21, 2014)
* Tethys News (sent a writer, January 20, 2014)
* Kronos Star (sent Cato Rossini, Marcella Trapani to live blog, January 20, 2014)

<br>

On January 20th, following the updates from the writes that were sent to sites, these sources looked like derivative sources that wrote overviews of the events:

* News Desk (818.txt)
* The General Post (107.txt)
* The World (49.txt)
* The Tulip (712.txt)
* The Explainer (397.txt)

<br>

On January 21th, following the updates from the reporters of Modern Rubicon and The Abila Post at 10:13 (that CEO Sten Sanjorge, Jr. was not among the missing GAStech employees). These are the sources that we identified as derivative sources:

* The Truth (463.txt)
* The Light of Truth (822.txt)
* The World (824.txt)
* The General Post (536.txt)
* Who What News (310.txt)
* The Guide (62.txt)
* International News (689.txt)
* Worldwise (752.txt)

<br>

On January 21th, in addition to the above sources, the following derivative sources are still reporting the event of yesterday:

* International Times (167.txt)
* The Continent (245.txt)
* World Journal (396.txt)
* Everyday News (460.txt)
* World Source (787.txt)

<br>
<br>
<br>
<br>

<hr style="border:0.5px dashed black"> </hr>
