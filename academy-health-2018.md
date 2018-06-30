# Academy Health

<div align="justify">

### Date

24-26 June, 2018

### Setting

Seattle, WA, USA


## Summary

### TL;DR

* Cochrane is using technological innovations to substantially improve the process of creating systematic reviews
* Better partnerships between academia and industry can substantially facilitate innovation
* Scientists in health services research are becoming incresingly interested in machine learning techniques

### Cochrane's next generation evidence systems

Cathy Gordon of Oregon Health and Science University presented [Cochrane Crowd](http://crowd.cochrane.org/index.html), a platform where any member of the public can help speed up the process of systematic review. So far, the public has been instrumental in identifying randomzied controlled trials much more rapidly and with much less resources than would previously be necessary. They are now using the crowd to identify tables within PDFs. They also have a learning zone where members can get badges for completing training in things such as "Expert opinion alone is not enough" or "The role of blinding". What a fantastic initiative! Cochrane has managed to establish itself on the top of the evidence-based medicine food chain and I hope they keep using their role responsibly, even though the presentation by Julian Elliott was rather worrying on that front.

Julian Elliott presented a few technological solutions for more efficient and living systematic reviews. First, he presented [Covidence](https://www.covidence.org/home), a platform that makes running systematic reviews easy - this is a non-for-profit organization and their software appears great, but it is disappointing that it is so expensive ($ 240 for one review, $445 for three reviews). Second, he indicated that RevMan, the Cochrane tool for meta-analyses, is now revamped and available as a web app [here](http://community.cochrane.org/help/tools-and-software/revman-web) - this does not seem to be available to the public yet. Third, he indicated that they are working on constantly updated systematic reviews with [Prof. James Thomas](https://iris.ucl.ac.uk/iris/browse/profile?upi=JTHOA32) of UCL. Fourth, they are working on developing ontologies in terms of PICO to identify similar sytematic reviews, make knowledge discovery faster and identify gaps in knowledge. An overview of this can be found [here](http://linkeddata.cochrane.org/pico-ontology), but access is restricted to the public. A company working on the exact same thing is Epistemonikos and their platform can be found [here](https://love.epistemonikos.org/#/). This is being developed with money from the Bill and Melinda Gates foundation, Robert Wood Johnson foundation and expertise from Microsoft Research. It is unfortunate that these efforts are not open and that the data being used are not open.

### NLM Town Hall: Future of scholarly communication and HSR

This did not discuss any of the topics I was hoping to hear about, such as utilizing 21st century technology to substantially improve scholarly communication and knowledge discovery. The most interesting talk to me was that of Jennifer Hansen, who presented the platform created by the Bill and Melinda Gates Foundation to make all research funded by that Foundation open. This is now inceasingly common - WellcomeTrust also has such a platform and the European Union is working on such a platform.

### Moving beyond p < 0.05; making health services relevant to the C-suite

This session featured members of the C-suite, such as Russell Holman (LifePoint Health), Ashish Jha (Harvard) and Francis Chesley (AHRQ) giving advice on how to make health services research more relevant to administrative staff. The main take-away message was that we need to have the future application in mind when embarking into new research. A comment by a member of the audience that this session should have not been about how researchers can make their work more relevant to the C-suite, but rather how the C-suite could communicate more effectively with researchers brought claps and enthusiasm.

### Luncheon plenary part 1:  Lunch and Award presentations

Richard Frank of Harvard University received the distinguished Investigator award. Mitesh Patel of University of Pennsylvania received the Alice S. Hersh New Investigator Award. Patel's work on using behavioural interventions to improve health sounded phenomenal.

### Luncheon plenary part 2: Innovation and the future

A discussion between Porsche Everson (Relevant Strategies), Dave Chokshi (NYC Health) and Robert Califf (Verily, Duke, ex-FDA Chair) on what is innovation and how this can be stimulated. A lot was said about the difficulty of innovating within the current research environment and the usefulness of partnerships with the industry. Prof. Califf was asked to comment on the recent initiative by Amazon, Berkshire Hathaway and Chase, which he said has the opportunity to substantially change primary care, even though specialty care would be harder to change. I was very interested in his note that each user of Google Search participates on average in 3 randomized controlled trials - I wish we could be doing the same with our healthcare systems so that everything we do is part of a trial and that we use every opportunity available to us to learn effectively.

### Machine learning and applications to health services and health care

This was a general tutorial on what is possible with machine learning methods in health services research. Edwin Wong gave a brief introduction on machine learning methods and how the package `caret` can be used for fitting all sorts of models - a great tutorial on caret can be found [here](https://www.machinelearningplus.com/machine-learning/caret-package/). Sherri Rose, the author of "Targeted Learning: Causal Inference for Observational and Experimental Data" with Mark J. van der Lann, illustrated how machine learning can be used for causal inference - very interesting work that reminded me of double machine learning; a great overview by Susan Athey of such methods can be found [here](http://www.nasonline.org/programs/sackler-colloquia/documents/athey.pdf).

### Application of learning algorithms to understand complex healthcare data

This session illustrated use-cases of machine learning methods to health services research. David Chen illustrated how his team developed a model to predict bleeding after colorectal surgery using gradient boosting. I was particularly interested in their use of the Boruta package in R to select important variables and reduce their parametric space - a great tutorial on how to use the Boruta package can be found [here](https://www.analyticsvidhya.com/blog/2016/03/select-important-variables-boruta-package/). Caroline Thirukumaran illustrated how they used natural language processing (NLP) with logistic regression to identify surgical site infections. The features they used for NLP were presence or absence of specific keywords - they did not use more complicated features or deep learning. They illustrated that models using free text were better than those using free text and additional covariates - I felt that them using a logistic with elastic net regularization would be a more natural method of coming to such a conclusion. Jiali Yan created a density-based cluster analysis of EHRs and then characterized the main features of each cluster. Steven Lippmann attempted to predict whether a patient has peripheral artery disease or not using the LASSO.

### Empirical evidence on the impact of incentives on consumer health behaviors and health care decisions

This primarily referred to using financial insentives to promote healthy behavior. The researchers tested whether financial incentives can improve adherence to exercise advice in those with ischemic heart disease and found a substantial positive effect. Very interesting perspectives on using such incentives to improve health by Mishra Patel. Interesting comment by another speaker that there is little correlation between quality and choice of provider because co-pay tends to be similar across any provider; as such, providers have no reason to compete on cost and quality.

### Using and improving EHRs for care delivery and communication

This session illustrated use-cases of electronic health records (EHRs) for health services research. Ragnhildur Bjarnadottir illustrated how she used text mining to analyze nursing notes and measure knowledge of fall-related factors. Megan Lafferty illustrated problems secondary to using archaic technology to communicate between health providers within the hospital (e.g. pagers) - she did not touch on why technological solutions that can address these problems are not more widely adapted.

### Overall

A great overview of research in health services, current limitations and future avenues.

</div>
