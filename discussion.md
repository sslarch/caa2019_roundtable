## Statement Martin Hinz

### Scientific Scripting Languages in Archaeology – Focussing on the Opportunities of Open Research

Every science, to be regarded as scientific in a general sense, is obligated to make the way in which it comes to its results transparent. Nearly every other science, except for, among few, archaeology. 

Admittedly, there are standards how to document an excavation as the basic way how we come to our raw data. But these standards are far from being unified, making in most cases the analysis of a previous excavation an adventure, if not a nightmare. But in recent years, overarching analysis have become more important then ever. This is absolutely necessary to make our subject a relevant one beyond antiquarian interest and the love of 'rare objects'. And especially these kind of investigations require to follow a certain standard of transparency, comprehensibility, if not reproducibility. This has been true before, but the current development of our subject has increased the demand substantially. I would envisage an investigation, were I do not have to believe the validity of the graphs resulting from some sophisticated analysis, but were I can work with the data and the workflow and verify that the nice pictures resulting from the analysis really represent the data in a meaningful way.

As the demands have risen, also the tools have. Or, actually, they have not, but we are kind of were the journey of computer aided archaeology had started: By publishing Code Listings and data together with the results of the analysis. I can remember that it felt funny when I saw publications with source code in Basic that reminded me to my early experiements with personal computers like the C64. But this style has vanished somewhen in the late 1970s/early 1980s with more and more complex analysis that would easily fill whole books on their own. But not everything was bad in those days.

What now is available, thanks to electronic (and not so well named digital) publication is the possibility to publish data and scripts alongside with the paper, without wasting all those pages any longer. And for this reason, what should stop us from remembering those good old pratices to make our shiny and brilliant analytical steps and interpretations accessible to our colleagues and proof, that our number crunshing is as educated as our theoretical background.

And this is where no other tool is as capable to at the same time produce an analysis and make it understandable to the human reader as it are scripting languages of whatever flavour. Of course, there are plenty of them, and no one can learn every one. But they make the analysis in principle accessible and at best reproducible, in the lack and as a replacement of standardised laboratorical workflows and analytical procedures that can be monitored by third parties. The heterogenity of our data often prevent us from following a best practise developed for other data. But (only) with the use of scripting languages we nevertheless can make our results scientific, without sacrificing the creativity and freedom necessary in our field of expertise on the interface between natural sciences and humanities.

That is why we think it is more than necessary to bring our efforts together, developing a new attitude and ethos of archaeological analysis with Scripting Languages, and convince colleagues still attached to graphical user interfaces how easy, if not even easier it is to use the same or better methods building on the power of the source. A whole world of Open Source Software development out there can not be wrong in this, and the ever growing success of Open Source in the scientific field vividly shows this.

## Statement Clemens Schmid

### (Don't Fear) The Reaper. A SIG as long term software maintenance network?

For about 50 years archaeologists have been using computational methods to answer archaeological questions. A considerable part of the many thousands of resulting papers relied on interpreted languages. Unfortunately, most of this software was never published or distributed in a reproducible way.

I suggest the Special Interest Group (SIG) for Scripting Languages in Archaeology (SSLA) to become a vehicle for software sharing and long-term maintenance. It should provide a collaborative and organizational framework for joint work and responsibility to create new and to prevent further loss of already established methodological knowledge.

There are several organisations trying to provide this service in a research subject agnostic way, most notably the [rOpenSci](https://ropensci.org/) community. rOpenSci members develop research software in R, provide code reviews for their colleagues, promote releases and use cases, and pick up relevant projects that are at risk of getting lost due to -- among other things -- changes in employment situations, illness, or even the death of maintainers.

I admire this project, but I also believe that it has two main weaknesses: Its limitation to R and its interdisciplinarity. Neither is inherently bad, but for the specific applications of archaeology and cultural anthropology, a more thematically focused and technically open community might be more appropriate. The SIG SSLA could close that gap.

How exactly could this work?

1. SSLA members could register sufficiently generic projects as part of the SSLA software family. These projects would have to meet certain requirements concerning reproducibility and maintainability, but could then enjoy the stewardship of the SSLA community.
2. SSLA members could enlist in a network of mutual technical support and code review.
3. A quarterly report could list developments in the Archaeology-Scripting languages world in collaboration with already established software lists, like e.g. [Ben Marwicks CRAN Task View: Archaeological Science](https://github.com/benmarwick/ctv-archaeology) or [Zack Batists Open Archaeology Software list](https://github.com/zackbatist/open-archaeo).

