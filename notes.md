[Slide 1]('https://mjlavin80.github.io/DHworkshop-CMU-2017/slides/index.html#1')

Writing an introduction for digital literary studies is a daunting task. To do so, one must agree to wrestle the great bear that is literary studies or, perhaps even more dauntingly, that ubiquitous institution known as The English Department. Members of English departments might be familiar with some of the labels on this slide:

[Slide 2]('https://mjlavin80.github.io/DHworkshop-CMU-2017/slides/index.html#2')

But here today I want to weave in some discussion of a few specialties that might be less familiar:

[Slide 3]('https://mjlavin80.github.io/DHworkshop-CMU-2017/slides/index.html#3')

Digital literary studies is probably the most established of all digital humanities subfields, the most varied in terms of its practitioners' motivations and position-takings, and the most often discussed in the discourse we might conveniently label "public-facing digital humanities." Most practitioners in literary studies have at least heard of distant reading.
As a result, digital humanities literary analysis is often central to public criticisms of digital humanities as a field. I would argue, as would others, that treating dh in literary studies as a stand-in for the whole of digital humanities is fundamentally unfair, yet this is part of why it can be so daunting to summarize my particular scholarly subfield.  

Another one of the biggest challenges with describing a multifaceted, interdisciplinary space with a varied history is that I have multiple points of entry. Autobiography is one such option. I came out of the University of Iowa's English department and did my comprehensive exams straddling the methodologies of of new historicism and book history. And most of my published work has been specifically focused on Willa Cather from a bibliography, book history, and authorship studies perspective. Prior to serving as a CLIR Postdoctoral Fellow at the Center for Digital Research in the Humanities at the University of Nebraska - Lincoln in 2012, my tie to the digital was my claim as "a guy in the department who knows stuff about computers." After Nebraska, I had an alt-ac position managing a Mellon-funded digital humanities/integration/collaboration grant at St. Lawrence University in Canton, NY. Two years ago, I started at Pitt in another alt-ac role: Clinical Assistant Professor of English and Director of our Digital Media Lab. As a result of these choices, I've now spent about four years developing computational skills in pedagogical and research contexts. So for me, what it feels like to be situated within digital literary studies can be as complicated as my position on post-structuralist questions of representation, or my views on the implicit position-takings of algorithmic or quantitative thinking. Simultaneously, the question has been as concrete as which building my office was in, what I was allowed or required to teach, and who was likely to skip a meeting if the agenda related to digital humanities.

[Slide 4]('https://mjlavin80.github.io/DHworkshop-CMU-2017/slides/index.html#4')

Another point of entry is that of historicism. Almost any summary of the field will tell you that digital literary studies includes the markup tradition associated with textual and documentary editing (e.g. TEI) and, to tell the story of that subfield, I might begin with Jerome McGann's excellent work on textual editing. For the purposes of this talk, however, I want to raise a distinction between this markup based tradition and the perhaps more controversial subfield of computational text analysis.

[Slide 5]('https://mjlavin80.github.io/DHworkshop-CMU-2017/slides/index.html#5')
[Slide 6]('https://mjlavin80.github.io/DHworkshop-CMU-2017/slides/index.html#6')

In contrast to the markup tradition, computational text analysis has roots in both "Humanities Computing" and stylometry, which includes pre-computing attempts to make literary study a quantitative enterprise. As Andrew Jewell has eloquently argued, this quantitative work can be traced at least as far back as Lucius Sherman's 1893 monograph.

[Slide 7]('https://mjlavin80.github.io/DHworkshop-CMU-2017/slides/index.html#7')

To quote Jewell, "Sherman was the author of Analytics of Literature (1893), a book which articulated Sherman's system for the 'objective study' of literary prose. This system, which, among other things, computed the 'force-ratio' in passages, or the number of emphasized words in relation to the number of total words, involved a good deal of counting by Sherman and his students, and Sherman's methods inspired a healthy amount of ridicule."

Most contemporary practitioners of computational analytics would distance themselves from figures like Sherman if given the chance, but the specter of Sherman (and voices like his) are so present among our less digitally inclined colleagues that it behooves us, as Jewell argues, to confront that legacy directly. That said, we should also claim the best of our Humanities Computing heritage, and in this I would include the pioneering work of Roberto Busa and the profound impact of Willard McCarty, among others.

A third point of entry is to use large scale methods to survey a small corner of literary studies discourse. Andrew Goldstone and Ted Underwood generated two different sets of topic models of 5,940 articles in PMLA, one generating 150 models covering 1924 to 2006 and another generating 100 models covering 1890–1999. For those of you who don't know, topic modeling has to some degree "taken DH by storm" in the past few years, as it's the kind of tool that digital humanities can really sink their teeth into. The idea is to use statistical inference to generate lists of co-occuring words across multiple documents. If you think about how topics of discussion in written materials work, it's reasonable to assume any given document in a set discusses more than one topic, and that any given topic could easily occur in more than one document. Checking co-occcurences one at a time across documents would take a theoretically insane amount of time, so we probabilistic methods instead. And there are in fact many statistical approaches to modeling topics. In most cases, we set a somewhat number of topics we want our algorithm to find, say 50, 100, or 250, but not three or four. What all this means is that if we run the exact same topic modeling setup over and over again, we will get slightly different results each time. Further, the PMLA visualization only goes to 2006 and thus does not reflect the post-2008 surge of interest in digital humanities. Even if we did update this particular line of inquiry, however, Goldstone and Underwood remind us that the PMLA is just one journal, and the DH boom has been as much about new publications, and new modes of communication, as it has been an intervention in the trajectory of the existing literary studies field. I mention all this way of explaining and qualifying topic models for those of us who are new to digital humanities.

Before lapse completely into talk of methods, I want to linger on Underwood and Goldstone's findings. In their accompanying blog post for "The Stone and the Shell," Goldstone and Underwood draw various conclusions from this set of topic models, but I want to highlight one in particular:

[Slide 8]('https://mjlavin80.github.io/DHworkshop-CMU-2017/slides/index.html#8')

The topic model "evidence found fact time note part early professor appears made ff passage case source date connection present similar find" experienced a steady drop in prominence over time. At some point in the history of literary history, our keywords and phrases shifted away these terms into dialogic and critical vocabularies, terms like "cultural," "theory", "text" and "the self." From one point of view, computational text analysis is a return to the quantitative. This is generally true of both textual studies and formalism--the two most dominant interpretive frames in digital literary studies. What counts as evidence and how that evidence makes meaning varies significantly between these schools of thought, but Goldstone and Underwood's work points to a serious challenge facing practitioners of digital literary studies today: the fact that an entire generation of literary scholars were heavily influence by the critical theory movement, which lodges a substantial critique against totalistic systems of empiricism and quantification. Many digital humanities scholars have attempted to meet this challenge by arguing that digital humanities is, at its best, both an engagement with and critique of something loosely akin to "logical positivism," but others have been content to urge the humanities to be more quantitative and evidence-driven. To engage in digital literary studies, ultimately, is to confront the tensions and gains associated with genuine differences of perspective. It remains important, regardless, to try and appreciate why computational analysis and distant reading might make some of my departmental colleagues uncomfortable.

As the founder of a website called humanitiesdata.com, I'm probably biased. I've called for DH to embrace,
"A culture of openness and collective access to shared digital objects of study" in order that we might ...

[Slide 9]('https://mjlavin80.github.io/DHworkshop-CMU-2017/slides/index.html#9')

- Collaborate more effectively
- Interrogate and invalidate insufficiently rigorous scholarship
- Verify and build upon excellent scholarship
- Avoid duplicating the intense labor of data creation and normalization
- Learn new methods and approaches at a pace that’s consistent with the speed at which DH moves

Is this positivism? Is this pseudoscience or scientism? I would argue that embracing a culture of open data need be none of these things. Rather, I promote a set of principles based on that idea that truly collaborative scholarship is only strengthened by efforts to create or make more accessible the objects of study that we have in common.

On this note, I want to transition to more of some literary studies DH work that I think is really representative of the computational side of the discipline (and in general work that I really like, though I'm sure I've left out many great pieces here). Much of the scholarship I'll discuss is tentative, or incomplete, or overdue for an update, but that's the nature of digital humanities. In fact, one of its greatest strengths is its interest in continuing to refine its methods and reach new insights, often through collaborative effort. Hence humanitiesdata.com (last plug, I promise).

I've organized the rest of my talk around groupings for textual analysis methods. If any of you saw me speak at Duquesne this February, this categories will be familiar, although I have changed up some of my key examples to reflect newer work or things I've recently discovered:

[Slide 10]('https://mjlavin80.github.io/DHworkshop-CMU-2017/slides/index.html#10')
