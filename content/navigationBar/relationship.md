---
draft: false
lightgallery: true
---

<br>
<br>

## Relationship

### First Intuition

Looking at the `email headers` dataset, we first think of plotting it as a network plot showing the connection between employees at GAStech.

To begin with, we used a chord diagram. The connection is shown below, and we can hover on each person to see specific insights.

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://email-chord.netlify.app/" height="650" width="100%"></iframe>

<br>
<br>

However, even though the diagram looks pretty, it's **not** really informative. People who email others a lot, namely, **Mat.Bramar** and **Ruscella.Mies.Haber**, are all administrative assistants whose job is helping their manager to connect with other people. So them sending and receiving emails isn't suspicious.

### Nest Step

Not finding much useful information from the chord diagram, we decided to plot a heatmap with a slider that enables us to show email connection each day. Because we suspect the chord diagram didn't show much info as it described the overall relationship, but there might be problematic connections on some specific day that the chord diagram overlooked. So here comes the heatmap. If we hover on each connection in the heatmap, we can see the email sender and receiver as well as how many emails one sends to the other on that specific date.

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://email-from-to.netlify.app/" height="700" width="730"></iframe>

<br>
<br>

However, after looking closely at the heatmap, we still didn't find especially suspicious behaviors. Again, those who send more mails are mostly administrative assistants, and even though there is no email record on 01/11 and only one email record on 01/12, that is totally normal because those days are weekends. So we are again unsure what we should do next.

### More info

Then we plot a wordcloud displaying frequent used words in email subjects. There are some interesting phrases, such as, **vip visits**. Who are the they? What's their role in the events? However, because there are only email subjects, we cannot look into specific email to find out more details. So again we are stuck.

{{< image src="images/subject.png" alt="Wordcloud of Email subjects" caption="Email subjects" height="50%" width="50%">}}

### HELP

What should we do with the `email headers` dataset? Is there any information that we overlooked?

<!-- * Ale Hann
* Valentine Mies
* Jeroen Karel
* Henk Bodrogi
* Carmine Osvaldo
* Joreto Karell
* Yanick Cato -->

<br>
<br>
<br>
<br>

<hr style="border:0.5px dashed black"> </hr>
