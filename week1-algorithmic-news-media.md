## An Overview of Algorithmic News Media

<p>This is the beginning of the Knight Center for Journalism in the Americas course "News Algorithms: The Impact of Automation and AI on Journalism".</p>

### Algorithms in news production

<p>What do we use algorithms for in the news business?</p>

* Data mining
    * Can be used for factchecking, comment/content moderation, monitoring social media
* Automatically generate content
    * Also used for news bots, automatically creating articles, videos or data visualizations
* News distribution
    * Headlines testing or personalizing content for readers

### What do news algorithms do?

* Calculation
    * Scanning in a document and converting into machine-readable text (OCR)
* Prioritization
    * Finding the most important thing for a reader and showing it to them
    * Search results
* Classify
    * Who the Hell? NYT project that categorizes the faces of politicians
* Association
    * Panama Papers. Found asociations between the entities and the officers of shell companies
* Filtering
    * Important due to information overload issues. Facebook news feed is a filtering algorithm

### But humans still do stuff better!

* Good at complex communication
    * Actual reporting
    * Dealing with tough or hostile sources
* Expert thinking
    * Problem solving
    * Thinking through strategies, knowing when to switch it up
    * Deep knowledge of beats/domain
* Dynamic
    * Creativity

### Two big themes

* Human values

<p> People and their values are all embedded into the code that was written behind an algorithm. This runs the risk of including biases. It's not just math and science, there is a certain level of subjectivity within all algorithms.</p>

* Blending or hybridization

Algorithms are good at some things, while humans are good at others. We need to figure out a way to blend them together to get the most out of both us and computers.</p>

## Computational Story Discovery

<p> We're going to learn about one of the more promising uses of algorithms in the news industry. We're going to use the Atlanta Journal-Constitution [Doctors & Sex Abuse]("http://doctors.ajc.com") investigation.</p>

<p> We'll also look at a tool called [Newsorthy]("http://www.newsworthy.se/en/")</p>

### AJC investigation

#### How it came about

* Reporters noticed that there seemed to be a bunch of doctors who faced disciplined for sexual misconduct but continued to practice medicine

#### How did they get the data

* First read hundreds of documents (a subsample) and tagged them as interesting or unintersting in terms of what they were looking for
* Then trained a classifier (standard logistic regression model) to look for patterns of words that were either associated with interesting or uninteresting cases
* Scraped more than 100,000 documents and ran them through the classifier and got 6,000 that were interesting
* Reporters read through those to get the basis for the story

### Newsworthy

<p>A tool that monitors datasets and reports anomilies that might make good news stories.</p>

#### What it can do

* Pick a region or beat and recieve alerts when something interesting pops up in the data


### Claimbuster

<p>Rates things true or false.</p>

#### What it can do

* Identifies fact-checkable claims
* Assign scores to rate the "trueness"
* Duke University uses it to fact check CNN every day

### Reuters Tracer

<p> Monitors millions of tweets and clusters them</p>

#### What it can do

* It's super fast — in tests beat out 84% of news organizations
* Identifies newsworthy events

### So why is computational story discovery so great?

* Makes investigations more comprehensive
* Help draw attention to events or data that might be newsworthy
* Speed: In breaking news and news and document gathering

#### But keep in mind

* Make sure you're covering something because you want to, not just at the behest of the tool
* Don't get overwhelmed
* Still need human journalists

## Computational Thinking

<p>How can you integrate automation, AI and machine learning into your editorial workflow.</p>

> "The though processes involved in formulating problems and their solutions so that the solutions are presented in a form that can be effectively carried out by an information-processing agent." — Jeannette Wing, Columbia University

### What is computational thinking about?

* It's not about thinking like a computer
    * Thinking in a way that allows you to use computers to solve problems
* Abstraction
    * Being able to see a specific problem and realizing its part of an abstract and more general problem
    * Then you can solve it over and over again
    * Modeling, decomposition and parameterization* Scale
    * Not just one use/story, 100, 1,000 or 100,000

* Not programming per se
    * Organizing a solution so it could be programmed

> “Effective production is more likely to require both human and machine inputs, and the value of the human inputs will grow, not shrink as the power of machines increases... It's great to be a complement to something that's increasingly plentiful.” — Brynjolfsson and McAfee, The Second Machine Age

### Let's dig into abstraction

#### Modeling

* Allows us to represent information for computers
* Create a dumbed down version of reality for computers
* Apple News' "for you" section, a model of me based on geography or other stuff

#### Decomposition

* Pulling apart the steps of a process
* Breaking up complex tasks into many simple tasks
    * Helps start thinking through whether humans or computers should do a task
* Breaking down writing an article: collect data, identify trends, etc., etc.

#### Parameterization

* Let's look at the recipe example
    * Can make regular or vegetarian cake
    * Eggs in the recipe to adhere other ingredients
    * Could use another binding agent: flaxmeal
    * Parameter of eggs for regular and parameter of flaxmeal for vegetarian

