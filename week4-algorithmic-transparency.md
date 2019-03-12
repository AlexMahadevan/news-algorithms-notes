## The algorithms beat

<p>This week, we focus on how to cover algorithms as a journalist.</p>

### Covering algorithms 

<p>How to unlock the mystery behind AI, machine learning and algorithms</p>

* Algorithms are everywhere
    * Used to ptimize everything from transit planning to romantic dating
    * This is a problem since algorithms aren't accountable
        * Dating apps setting up incompatible couples is a small example

* ProPublica and criminal risk assessment
    * Covered algorithm that measured when someone is a high risk to commit a crime
        * Used for parole and sentencing decisions
    * Found black defendants were scored higher than white defendents
    * Shows how algorithms can create bias

* Newsworthiness
    * If an algorithm makes a bad decision, what does it mean for individuals or society?
        * Black defendants unfairly targeted with harsh sentences or denied parole
    * Does it violate expectations?
        * Algorithm does — or doesn't — do something it's supposed to do
    * What's the public si9gnificance of the above?
        * Bad movie recommendation may not be newsworthy, while something like an algorithm that vets resumes in a biased way — racism, ageism, sexism — has a more prfound impact on society

### Practical advice for algorithm angles

<p>How to find an angle to cover a certain algorithm.</p>

* Discrimination or unfairness
    * The ProPublica story is a good example
    * Look for all flavors of bias 

* Erros and mistakes
    * Guy had his drivers license revoked because fraud-ID algorithm misidentified him

* Has it violated the law or social norms?
    * Example: Algorithm that writes automated news mistakenly libels someone :grimacing:

* Human misuse
    * Algorithmic decisions are embedded in larger system, if the people in this system misuse the algorithm, then it's newsworthy
    * In ProPublica piece, prisons were using womens algorithm for male inmates

## Algorithmic accountability reporting methods

<p>Let's talk through some methods to reporting on algorithms.</p>

### Getting the story

<p>Marry new techniques with old, and use a variety of technical and non-technical method to invertigate algorithms.</p>

* A diverse team is key
    * Traditional journalistic skills:
        * Reporting
        * Editing
        * Writing
        * FOIA
    * New techniques
        * Scraping data
        * Knowledge of advanced statistical techniques

* How to get the story
    * Reverse engineering
        * Trying to uncover the tech specs
        * Looking at the variables and how does it weight those variables
        * "Inside the Algorithm That Tries to Predict Gun Violence in Chicago" — The Upshot
            * Got data on scores and variables from Chicago PD
            * Built their own model and able to predict scores
    * Auditing
        * Looking at inputs and outputs for errors or other patterns
        * Comapring inputs and outputs against benchmarks, see if they're skewed or biased
        * "Websites vary Prices, Deals Based on Users' Information" — WSJ
            * Studies dynamic pricing, how prices vary by location
            * Picked a website and simulated different users visiting from different locations, recorded the price on the website
    * Poking and prodding
        * Try it out yourself
        * "How I Cracked Facebook's New Algorithm and Tortured My Friends" — BuzzFeed news
            * Posted something annoying, got a lot of comments, algorithm made it sticky, people who commented kept seeing it over and over at the top of their feeds
    * Crowd sourcing
        * Data donation drives: Asking readers to send in their results
        * Der Spiegel investigation of credit score algorithms
        * Downside: Sample is usually biased
    * Code review
        * Literally reading the source code of the algorithm
        * No always applicable
        * "What Happens When an Algorithm Cuts Your Health Care" — The Verge
            * Medicaid assessment algorithm was supposed to show how many hours someone "deserved" a caretaker 
            * Lawsuit revealed third-party company in charge of implementing algorithm used the wrong version!

## Editorial responsibility & algorithmic transparency

<p>How should journalists hold themselves accountable with our use of algorithms?</p>

* How do you be transparent about your news algorithm?
    * Study to determine how much information to make public
    * Four areas: 
        * Data
            * What data is used in the system. Comprehensive? Quality?
        * Model
            * What variables is it using and how are they weighted? How was the machine learning trained?
        * Inference
            * Accuracy or error rates of inferences
        * Interface
            * The system itself
        * Human involvement
            * How were humans involved in planning?

* Example: "The Tennis Racket" — BuzzFeed News
    * Article is linked to high-level and accessible description of the methodology (complete with gifs!)
    * Linked GitHub repo that showed the code

* Challenges with transparency
    * Costs time and money to document EVERYTHING
    * Concerns over privacy — can you disclose all of the data?
    * Trade secrets and competetive advantage
        * Might come up in algorithms for personalization and curation
    * Manipulation and gaming
        * If you're totally transparent you might allow people to game your system to have their content more recognized by your algorithm
    * Cognitive complexity
        * Will people even look at documentation?
        * The point isn't that everyone needs to understand, but rather that it's available to some subset of people who can make use of transparency
        * Buzzfeed solved it in increasing levels of 

## Guest lecture: Christina Elmer | Der Spiegel

<p>A deep dive into how Der Spiegel has investigated algorithms</p>

* Projects started as collaboration across the newsroom in 2017. Then joinred forces with an NGO that evaluates algorithm

* Does the Google filter bubble really exist?
    * Looking at news results you don't see many differences

* Partnerships are key in large scale algorithmic investigations

* Skills needed in newsrooms
    * Need your own data journalism department
        * need in-house team that can handle huge amount of data/documents and write code for analysis
    * Need a deep understanding of the methodoloy you use

* Challenges of investigating algorithms
    * Project management
        * Lot's of partners and pieces
    * Private companies
        * Set up experiments to test algorithms 

* Advice for those getting into th algorithm beat
    * Just do it — such an important topic
    * But be aware of limitations in undertaking this with small teams

* How to promote transparency?
    * Think of the audience: Like the Buzzfeed piece, do different iterations of methodology based on complexity