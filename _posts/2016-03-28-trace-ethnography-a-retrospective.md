---
title: 'Trace Ethnography: A Retrospective'
date: 2016-03-28T18:55:01+00:00
---
_This is a cross-post of [a post I wrote](http://ethnographymatters.net/blog/2016/03/23/trace-ethnography-a-retrospective/) for Ethnography Matters, in their [&#8220;The Person in the (Big) Data&#8221; series](http://ethnographymatters.net/editions/the-person-in-the-big-data/)_

When I was an M.A. student back in 2009, I was trying to explain various things about how Wikipedia worked to my then-advisor David Ribes. I had been ethnographically studying the cultures of collaboration in the encyclopedia project, and I had gotten to the point where I could look through the metadata documenting changes to Wikipedia and know quite a bit about the context of whatever activity was taking place. _I_ was able to do this because_Wikipedians_ do this: they leave publicly accessible trace data in particular ways, in order to make their actions and intentions visible to other Wikipedians. However, this was practically illegible to David, who had not done this kind of participant-observation in Wikipedia and had therefore not gained this kind of socio-technical competency.

For example, if I added “{{db-a7}}” to the top an article, [a big red notice](https://en.wikipedia.org/wiki/Template:Db-a7) would be automatically added to the page, saying that the page has been nominated for “[speedy deletion](http://enwp.org/WP:CSD).” Tagging the article in this way would also put it into various information flows where Wikipedia administrators would review it. If any of Wikipedia’s administrators agreed that the article met speedy deletion criteria A7, then they would be empowered to unilaterally delete it without further discussion. If I was not the article’s creator, I could remove the {{db-a7}} trace from the article to take it out of the speedy deletion process, which means the person who nominated it for deletion would have to go through the standard deletion process. However, if I was the article’s creator, it would not be proper for me to remove that tag — and if I did, others would find out and put it back. If someone added the “{{db-a7}}” trace to an article I created, I could add “{{hangon}}” below it in order to inhibit this process a bit — although a hangon is a just a request, it does not prevent an administrator from deleting the article.

<div class="wp-caption aligncenter" style="width: 755px; border: 0;">
  <p>
    <img class="aligncenter" src="http://i2.wp.com/upload.wikimedia.org/wikipedia/commons/thumb/5/5b/Wiki_Women%27s_Edit-a-thon-1.jpg/800px-Wiki_Women%27s_Edit-a-thon-1.jpg?resize=680%2C453&ssl=1" alt="File:Wiki Women's Edit-a-thon-1.jpg" width="745" height="496" />
  </p>
  
  <p class="wp-caption-text">
    <em>Wikipedians at an in-person edit-a-thon (the Women’s History Month edit-a-thon in 2012). However, most of the time, Wikipedians don’t get to do their work sitting right next to each other, which is why they rely extensively on trace data to coordinate render their activities accountable to each other. Photo by <a href="https://en.wikipedia.org/wiki/File:Wiki_Women%27s_Edit-a-thon-1.jpg">Matthew Roth, CC-BY-SA 3.0</a></em>
  </p>
</div>

I knew all of this both because Wikipedians told me and because this was something I experienced again and again as a participant observer. Wikipedians had documented this documentary practice in many different places on Wikipedia’s meta pages. I had first-hand experience with these trace data, first on the receiving end with one of my own articles. Then later, I became someone who nominated others’ articles for deletion. When I was learning how to participate in the project as a Wikipedian (which I now consider myself to be), I started to use these kinds of trace data practices and conventions to signify my own actions and intentions to others. This made things far easier for me as a Wikipedian, in the same way that learning my university’s arcane budgeting and human resource codes helps me navigate that bureaucracy far easier.<span id="more-10287"></span>

This “trace ethnography” emerged out of a realization that people in mediated communities and organizations increasingly rely on these kinds of techniques to render their own activities and intentions legible to each other. I should note that this was not my and David’s original insight — it is one that can can be found across the fields of history, communication studies, micro-sociology, ethnomethodology, organizational studies, science and technology studies, computer-supported cooperative work, and more. As we say in the paper, we merely “assemble their various solutions” to the problem of how to qualitatively study interaction at scale and at a distance. There are jargons, conventions, and grammars learned as a condition of membership in any group, and people learn how to interact with others by learning these techniques.

The affordances of mediated platforms are increasingly being used by participants themselves to manage collaboration and context at massive scales and asynchronous latencies. Part of the trace ethnography approach involves coming to understand why these kinds of systems were developed in the way that they were. For me and Wikipedia’s deletion process, it went from being strange and obtuse to something that I expected and anticipated. I got frustrated when newcomers didn’t have the proper literacy to communicate their intentions in a way that I and other Wikipedians would understand. I am now at the point where I can even morally defend this trace-based process as Wikipedians do. I can list reason after reason why this particular process ought to unfold in the way that it does, independent of my own views on this process. I understand the values that are embedded in and assumed by this process, and they cohere with other values I have found among Wikipedians. And I’ve also met Wikipedians who are massive critics of this process and think that we should be using a far different way to deal with inappropriate articles. I’ve even helped redesign it a bit.

Trace ethnography is based in the realization that these practices around metadata are learned literacies and constitute a crucial part of what it means to participate in many communities and organizations. It turns our attention to an ethnographic understanding of these practices as they make sense for the people who rely on them. In this approach, reading through log data can be seen as a form of participation, not just observation — if and only if this is how members themselves spend their time. However, it is crucial that this approach is distinguished from more passive forms of ethnography (such as “lurker ethnography”), as trace ethnography involves an ethnographer’s socialization into a group prior to the ability to decode and interpret trace data. If trace data is simply being automatically generated without it being integrated into people’s practices of participation, if people in a community don’t regularly rely on following traces in their everyday practices, then the “ethnography” label is likely not appropriate.

Looking at all kinds of online communities and mediated organizations, Wikipedia’s deletion process might appear to be the most arcane and out-of-the-ordinary. However, modes of participation are increasingly linked to the encoding and decoding of trace data, whether that is a global scientific collaboration, an open source software project, a guild of role playing gamers, an activist network, a news organization, a governmental agency, and so on. Computer programmers frequently rely on GitHub to collaborate, and they have their own ways of using things like issues, commit comments, and pull requests to interact with each other. Without being on GitHub, it’s hard for an ethnographer who studies software development to be a fully-immersed participant-observer, because they would be missing a substantial amount of activity — even if they are constantly in the same room as the programmers.

**More about trace ethnography**

If you want to read more about “trace ethnography,” we first used this term in “[The Work of Sustaining Order in Wikipedia: The Banning of a Vandal](http://www.stuartgeiger.com/papers/cscw-sustaining-order-wikipedia.pdf),” which I co-authored with my then-advisor David Ribes in the proceedings of the CSCW 2010 conference. We then wrote [a followup paper in the proceedings of HICSS 2011](http://www.stuartgeiger.com/trace-ethnography-hicss-geiger-ribes.pdf) to give a more general introduction to this method, in which we ‘inverted’ the CSCW 2011 paper, explaining more of the methods we used. We also held a workshop at the 2015 iConference with Amelia Acker and Matt Burton — the details of that workshop (and the collaborative notes) can be found at[http://trace-ethnography.github.io](http://trace-ethnography.github.io/).

**Some examples of projects employing this method:**

Ford, H. and Geiger, R.S. “Writing up rather than writing down: Becoming Wikipedia literate.” _Proceedings of the Eighth Annual International Symposium on Wikis and Open Collaboration_. ACM, 2012. <http://www.stuartgeiger.com/writing-up-wikisym.pdf>

Ribes, D., Jackson, S., Geiger, R.S., Burton, M., & Finholt, T. (2013). Artifacts that organize: Delegation in the distributed organization. _Information and Organization_, _23_(1), 1-14. <http://www.stuartgeiger.com/artifacts-that-organize.pdf>

Mugar, G., Østerlund, C., Hassman, K. D., Crowston, K., & Jackson, C. B. (2014). Planet hunters and seafloor explorers: legitimate peripheral participation through practice proxies in online citizen science. In_Proceedings of the 17th ACM conference on Computer supported cooperative work & social computing_ (pp. 109-119). ACM. <http://dl.acm.org/citation.cfm?id=2531721>

Howison, J., & Crowston, K. (2014). Collaboration Through Open Superposition: A Theory of the Open Source Way. _Mis Quarterly_, _38_(1), 29-50. <http://aisel.aisnet.org/cgi/viewcontent.cgi?article=3156&context=misq>

Burton, M. (2015). Blogs as Infrastructure for Scholarly Communication. Doctoral Dissertation, University of Michigan.<http://deepblue.lib.umich.edu/bitstream/handle/2027.42/111592/mcburton_1.pdf>