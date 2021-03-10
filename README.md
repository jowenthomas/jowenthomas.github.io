# Projects<a name="projects"></a>

<div class="proj">
<h3>Mobile Apps: Partial Environmental Analysis</h3>
<p>From the perspective of gaps in market offerings that a new development company could leverage to launch a successful initial product, we aim in this project to understand trends in popular mobile apps. We will focus on behavior in the Google Play store and Apple iOS App store, and we will limit our attention to apps that are free to download and install. Broadly speaking, we will not account for political, economic, social, or legal factors, hence only performing part of the environmental analysis that such a company should complete.</p>
<p>Ultimately, we will identify three areas in the Apple store (reference, health and beauty, and catalogs) and five areas in the Google store (health and fitness, house and home, art and design, personalization, and tools) in which a novel idea has the room to rise to a prominent position in the "leaderboards." The reasoning for including these and exluding other popular categories is included in the course of our discussion.</p>

<a href="https://jowenthomas.github.io/business-applications/assets/pages/mobile%20apps%20environmental%20analysis.html">View Project</a>

<p>Tech: Pandas, numpy</p>
</div>

<div class="proj">
<h3>Product Reviews: Text Attributes</h3>
<p>This project is a step towards assessing whether or not a review was considered helpful based on the substance of the text review. To this end, in this project we aim to better understand the structure of our collections of reviews (included are 568,454 reviews from 256,059 users spanning 74,258 products), and do so by augmenting the given dataset with eight variables to reveal text attributes. Specifically, we establish the following:</p>
<ul>
  <li>Length: A simple measure of the length of each text</li>
  <li>LanguageDiversity: how rich is the language used</li>
  <li>DescriptorDensity: the frequency with which adjectives and adverbs are used to modify or amplify meaning</li>
  <li>MostFrequentDescriptors: a list of the words in the DescriptorDensity that are used with notable frequency</li>
  <li>LongWordDensity: a method of insight into the general accessibility of a text</li>
  <li>Personability: the amount of pronouns and possessives used in order to share personal experience</li>
  <li>Storytelling: the level to which a text provides a narrative structure</li>
  <li>SocialNetworkBinary: a binary measure of the extent to which a text leverages small group consensus</li>
</ul>

<a href="https://jowenthomas.github.io/business-applications/assets/pages/reviews.html">View Project</a>

<p>Tech: Python, Pandas, NLTK</p>
</div>

<div class="proj">
<h3>2020 IBM Data & AI Conference</h3>
<h4>Data & AI Essentials Workshop</h4>
<p>Through IBM Cloud Pak for Data, discussed standard practices for data wrangling, cleaning, preparation, and visualization.  Then, again working with the IBM CLoud Pak for Data as a Service, performed risk modeling for a lending scenario, based on UCI's German Credit dataset.  Discussed how to create projects within the environment, plug in data, integrate a cloud storage service, and associate a Watsom machine learning service instance via the API.  Performed data processing using a Data Refinery flow, including attribute removal and transformation, reviewing the automatic profiling, and exploratory visualization.  Reviewed the Watson Knowledge Catalogue and its functionality pertaining to data governance, quality, and consumption.  Then created a catalog, published our data asset to this catalog, and adjusted governance features to establish policies pertaining to data visibility of this public catalog.  Finally, we built a predictive model based on the random forest classifier algorithm with the SparkML API and saved it in the ML repository.  Completed this process with both Jupyter and AutoAI.</p>
</div>

<div class="proj">
<h3>Vocabulary for French Literature: A Systematic Approach</h3>
<p>Suppose you have been learning French and you feel ready to work your way through a reading list of French literature in French.  Using a corpus of eight classic texts, we let the texts themselves dictate which words we need to know in order to work through them. To do so, we will find the most common words (and look at some descriptive statistics to better define their utility) that occur within each individual text and across the entire corpus we have established for this project.</p>
<p>Ultimately, we will identify a subset of each text's vocabulary that provides at least 90% coverage of the text, specifically the subset of words that are used more than once. Note that this does not imply that we will have 90% understanding of the text. Many of the single-use words carry a disproportionate share of the meaning-passing within a sentence.</p>
<p>We finish by providing some functionality for exporting the results.</p>


<a href="https://github.com/jowenthomas/data-applications/blob/master/french-literature-vocabulary/french%20literature%20truncated.ipynb" target='_blank'>View Project on Github</a>

<p>Tech: Python, ebooklib, BeautifulSoup</p>
</div>


<div class="proj">
<h3>Employee Attrition: Supervised Segmentation</h3>
<p><a href='https://developer.ibm.com/patterns/data-science-life-cycle-in-action-to-solve-employee-attrition-problem/#description' target='_blank'>IBM</a> released data oriented towards identifying the cause of employee attrition.  We perform supervised segmentation on the given employee attributes and rank the most impactful individual variables that contribute to an employee leaving the company.  In the course of doing so, we provide a discussion on information gain and entropy, define and implement the pre-processing tasks required to execute our metrics, and identify fruitful paths for future work.</p>

<a href="https://jowenthomas.github.io/business-applications/assets/pages/attrition.html">View Project</a>

<p>Tech: Pandas, matplotlib</p>
</div>


<div class="proj">
<h3>Dashboard: MoMa Artist Demographics</h3>
<p>The Museum of Modern Art (MoMA) makes available data on the artists in their collection, which may be found on their <a href='https://github.com/MuseumofModernArt/collection' target='_blank'>github</a>.  Using these data, we have developed a dashboard that summarizes the available demographic information for the 15,236 artists included in their collection. </p>

<a href="https://public.tableau.com/profile/john.thomas3702#!/vizhome/MOMAArtistDemographics/Dashboard1" target="_blank">View on Tableau Public</a>


<p><strong>Summary of Findings:</strong>  Of the 15,236 artists included in the dataset, 12,105 possessed gender labels.  Of these, as represented in the pie chart, 81% were male, 19% were female, and there were 2 non-binary observations.  The dataset provided the year of birth and death for the artists, and our bottom-left histogram uses these to visualize an estimate of the time period in which the artists were active.  To do so, we have calculated the year of an artists midlife (as the average of birth and death year, using 2020 for those artists assumed to still be living), and our results show that almost exactly half of the artists in their collection were working in the second half of the 20th century.  This is rather expected for a collection of modern art, but it is noteworthy that their collection includes 412 instances from artists born after 1980 and 68 from artists working before 1850.  Follow-up work should increase the precision of these results by performing a similar analysis of the individual pieces in the collection.  Our histogram on the top-right of the Top N Nationalities represented (where N may be controlled by the user using the module on the right), indicates that European countries occupy 8 out of the top 10 positions (which also includes Japan and Russia) and that they account for 66% of all artists in the collection.  Follow-up work should also compare these results to the distribution for individual pieces.  Finally, to help understand the entire distribution of artist nationalities, we have provided a map of the countries associated to these provided nationalities.  This map overlays a color gradient, for which darker colors indicate a greater instance rate (note: because the high occurence of American artists within the collection, we have exluded them from the color overlay).  Brief additional comments are available in the dashboard by hovering over the help icon adjacent to each heading. </p>

<p>Tech: Tableau</p>
</div>

<div class="proj">
<h3>Dashboard: Top Book Publishers</h3>
<p>Using data made available by <a href='https://www.kaggle.com/ruchi798/bookcrossing-dataset#' target='_blank'>Ruchi Bhatia</a>, we have developed a dashboard that provides a snapshot of some key indicators for the top 15 publishers.  The dataset included observations for 271,379 books released, predominantly, between 1970-2009.</p>

<a href="https://public.tableau.com/profile/john.thomas3702#!/vizhome/BookReviews_15998434359980/BooksReleasedbyPublisher" target="_blank">View on Tableau Public</a>


<p><strong>Summary of Findings:</strong>  While the dataset did not label self-published works, our first visualization provides strong evidence (specifically, the number of publishers who released between 1-10 books) that they constitute a substantial portion of the market.  As such, any further exploration of market trends needs to account for the tools available to these individuals (certainly, such <a href='https://www.nytimes.com/2011/05/22/books/review/the-case-for-self-publishing.html' target="_blank">discussions</a> have occurred within the community for some time).  Our left-most pie-chart indicates that the top 15 publishers (with all of their subsidiaries or partnerships this is, in practice, 475 publishers) released a quarter of all books in the time periods reviewed.  Within this group, as indicated in the next pie chart, five publishers account for 51% of books released.  Our first histogram on annual activity highlights that the 1990's were the most active years.  Finally, our second histogram on user reviews indicates that a strong majority of books released are not reviewed, which holds across the top 15 fairly consistently.  </p>

<p>Tech: Tableau</p>
</div>

<div class="proj">
<h3>Applications of Linear Algebra</h3>
<p> The following articles serve to connect the topics in a linear algebra course to more modern and, hopefully, intriguing topics than is standard to discuss in the core curriculum.  Please note, these were written for use in the classroom and are, as such, more focused on discussion and exploration than a tight presentation of the results.</p>

<ul> 
  <li><a href="https://jowenthomas.github.io/linear-algebra-applications/">Introduction</a></li>
<li><a href="https://jowenthomas.github.io/linear-algebra-applications/assets/pages/matrices-as-images.html">Matrices as Images</a></li>
<li><a href="https://jowenthomas.github.io/linear-algebra-applications/assets/pages/higher-dimensions-and-linear-regression.html" >Higher Dimensions and Linear Regression</a></li>
<li><a href="https://jowenthomas.github.io/linear-algebra-applications/assets/pages/euclidean-distance-a-recommendation-engine-using-nearest-neighbors.html" >Euclidean Distance: A Recommendation Engine Using Nearest Neighbors</a></li>
<li><a href="https://jowenthomas.github.io/linear-algebra-applications/assets/pages/matrix-multiplication-to-find-connecting-flights.html" >Matrix Multiplication to Find Connecting Flights</a></li>
<li><a href="https://jowenthomas.github.io/linear-algebra-applications/assets/pages/adjacency-matrices-for-descriptors-in-dracula.html" >Adjacency Matrices for Descriptors in Dracula</a></li>
</ul>

<p>Tech: Python, NumPy, Matplotlib, SciPy, NLTK</p>
</div>



# Technology and Math<a name="techmath"></a>

**I spend most of my time using:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./assets/language_logos/python.png" alt="python" height="75"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="./assets/language_logos/sql.png" alt="sql" height="75"/>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./assets/language_logos/pandas.png" alt="pandas" height="75"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./assets/language_logos/seaborn.png" alt="seaborn" height="75"/>


**My mathematical interests are predominantly in:**

|Representation Theory | Harmonic Analysis  |   Abstract Algebra|
|Lie/Reductive Group Theory  |   Linear Algebra  |   Fourier Analysis|
|Functional Analysis|Graph Theory|

**Additionally, I am familiar with:**

|NumPy|Matplotlib|
|Scikit|SciPy|
|Git|





# Education<a name="education"></a>
Rutgers University, Ph.D. in Mathematics  

**Relevant subfields:** 
Harmonic analysis, Representation theory, (Algebraic/Lie) Group theory

**Dissertation:** 
Towards Stable-Stable Transfer Involving Symplectic Groups

**Overview:** 
Our work is situated at the intersection of two domains.  On the one hand, the methods of Fourier and harmonic analysis have been broadly applied, both in theoretical and applied work.  A testament to the robustness of the theory is the diversity of its applications, which include number theory, combinatorics, statistics, music theory, and physics, to name very few.  On the other hand, symplectic matrices, in part because of their volume and orientation preserving properties, have been receiving increasing amounts of attention in recent years.  For example, their utility is being leveraged in the development of quantum theory.

However, applying the methods of harmonic analysis to groups of symplectic matrices has been inhibited by the complicated structure of these groups. Our work achieves a fundamental perspective of this structure, which we refer to as the lattices of maximal tori, using direct methods, thus significantly reducing the amount of prerequisite knowledge for the reader.  We use this structure to develop the so-called transfer formulas necessary for performing the desired harmonic analysis.

**Abstract:** 
This thesis investigates the transfer formulas for orbital integrals, in the context of the modern Langlands' program for reductive algebraic groups. In the modern theory, there are two very different transfer theorems to be accomplished. First, there is endoscopic transfer, which relates, via an appropriate embedding of their L-groups,
a given group to a particular family of groups, its endoscopic groups. Here, deep theorems are known in great generality. Such a theory, however, is preliminary to the
second transfer, which is much less understood. At the same time, this second transfer is generally viewed as the more fundamental of the two, involving any connected
reductive group related to the given group by an L-homomorphism.

Prompted by the results for endoscopic transfer, our study focuses first on groups defined over an archimedean field. To do so, we study the geometric objects, orbital
integrals, on real or complex reductive Lie groups, for which there is a basic theory due to Harish-Chandra on which to build, focusing on the split and hyperbolic symplectic
groups to develop details. Concrete expressions of the final transfer formulas are notably different from those for endoscopic transfer, and the algebraicity condition
on the ambient group is critical in their development.

Specifically, our main focus is on a refined version of the structure of the lattice of maximal tori and on the role this plays in developing the concrete expressions for
transfer. Our structural results apply to symplectic groups of all sizes and their inner forms, and we develop an explicit transfer formula in the rank one case.


# Self-Study<a name="selfstudy"></a>
With my graduate work complete, I can focus the bulk of my attention on topics outside of pure math.  I will use this space to record courses, texts, or other materials I have found helpful.  In time, I would like to type up my additional documentation (e.g., problem solutions, summations), but for now, I will keep a simple list.

<a href='https://www.coursera.org/learn/machine-learning' target='_blank'>Andrew Ng Machine Learning</a>


UMN <a href='http://www.stat.umn.edu/geyer/s19/5101/' target='_blank'>Statistics 5101</a>


<a href='https://www.oreilly.com/library/view/data-science-for/9781449374273/' target='_blank'>Data Science for Business</a> by Foster Provost, Tom Fawcett


CMU <a href='http://www.cs.cmu.edu/~tom/10701_sp11/' target='_blank'>10-701: Machine Learning</a>


# Teaching Testimonials<a name="teaching"></a>
Having now left academia, it is invigorating to look back on my years of teaching and the many delightful students with whom I had the opportunity to work.  My average review as an instructor was 4.56/5.00 (on the particular question, "I rate the teaching effectiveness of the instructor as:"), compared to the department average of 3.95/5.00 over the same period.  


Some of the feedback I received: 


"Before I had John as my instructor my interest in math was close to zero. My previous instructors had never bothered to go into detail about the reasoning behind "Why are we doing this?" John has gone above and beyond what is required of him. It is hard to express into words the gratitude I feel towards him as my professor. After having taken his math course I truly am now interested in taking more advanced math courses despite not requiring them."


"He made me interested in a subject I usually struggle in and have me all the resources and materials needed to succeed in an effective and positive manner that made me actively want to learn."


"Thomas is an incredibly clear, effective and helpful instructor. He consolidates information to the very basics that you need to know to answer math questions properly. Some teachers over complicate things but Thomas does the exact opposite. Thomas is a fantastic teaching assistant and deserves to become a professor one day."


"Gave me advice that really worked with how i learn, he takes the time to understand what you struggle with. He also always tries to make time for extra hours when i need them."


"Made students believe all could be successful regardless of the fact that they might not love the subject."


"Professor Thomas was great, he always made sure that the class understood the material not only as numbers but as it relates to every day life. He made understanding mathematical concepts a lot easier. I would not change anything this semester. The professor was very helpful. "


"He has taught me to not only apply the formulas but to understand the story behind each math problem."


"Professor Thomas was the first math professor/teacher to actually teach in such a way that was more than just memorizing formulas and computing functions etc. I learned WHY certain things made sense and how one concept relates to another. The first my mind was blown was when I found out how to derive the derivatives of trig functions like secant etc, because I was only taught to memorize them. Another time my mind was blown was when I learned how to derive linear approximation from point slope formula. Overall an awesome teacher who told us constantly how smart and intellectual we are."


"This instructor was very supportive and patient. He offered help above and beyond the call of duty. I appreciate his availability as well as breaking the information down to my level of understanding."


"Professor Thomas is interested in student learning growth and does this through effective presentation of course material in addition to answering student questions. Review sessions were incredibly helpful along with the written exam study guides."


"He honestly inspired me to become more interested in the world of math."


"He was very open to questions and that helped with my understanding of statistics."


"Professor Thomas is awesome, super thankful for his disciplined way of teaching!"


"He taught me to think outside the box and everything is not as simple as it seems."


"The way he presented the material made it so easy to comprehend everything. It actually made me look forward to going to class and made me want to learn everything. 15/10 I would take John Thomas again as a professor because of how well he taught, as well as encouraging us to do our best. I’m extremely grateful to have taken this course with him and i’m glad I took this summer class!"


"Thomas is a great professor, he understands students and give them the opportunity to solve problems in their own ways as long as they use algebra, he explains the material really well , and encourage students to learn the reason why we need math."


"He is a really good professor! He made sure we understood the information and always showed great enthusiasm whenever students asked a question. I understood all the lessons he taught and the notes were really useful!"


"John i thought you were good in English but it seems your great in math too you are such a great well rounded individual and i truly look up to you"


"Created a very good learning environment. Very helpful and approachable."


"I really appreciated all the things this professor did. He made sure we understood the course content and always developed new way of explaining things to make it easier for us. Also, he made a sheet with a bunch of problems on it so we can use it to practice because he saw the class was struggling with it. I haven't seen this level of care from any other professor and i believe this professor should continue doing what he is doing."


"This professor is simply amazing. Tries his hardest to help you learn the material and to succeed in the course. Truly cares about his students and their academic standing."


"Instructor was enthusiastic about course which made it more interesting than listening to a monotone mundane professor who only cared because of his/her pension. The instructor also didn't assume you knew certain things and didn't make you feel "dumb". Great respect was shown to each student and his/her questions."


"I loved " think outside of the box" exam questions. I think John Thomas is very talented teacher. He was always prepared and the most important engaged in his classroom. "


"The instructor has increased my confidence in Calculus.He is the best maths instructor I have ever met."


"Instructor explained carefully the meaning of each lesson and examples so that i wasn't just a notebook copying down formulas but that I actually understood the lessons."
    
    
"Constantly encouraged us to ask questions if we had any trouble. Motivated us to not be intimidated by the concepts but instead tackle them with an open mind. "
    
    
"This course is now in my top two favorite courses I've taken since I've begun college. The other is also my previous math course and I had never really liked math."
    
    
"I really liked the professor and how he not only just gave us a formula and taught us how to do it, but he made sure we understood why we were doing that. I also liked that he tried to use analogies and examples in order to help the students understand better."
    
    
"Is probably one of the best math classes I have had. The fact that we had to justify answers in exams, forced me to not only just plug in a formula but also know the purpose of it. "


"Professor clearly put in plenty, if not, a surplus of effort to teaching the course and getting his ideology about learning across to his students. Very rare in Rutgers professors."
