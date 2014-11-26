Abstract
--------

Introduction
------------

The merits of reproducible research are widely acknowledged by scholars
in out field [e.g., (Mesquita et al. 2003); (King 1995); (Rich 2013)].
Although few political science journals have clear replication policies
(Gherghina and Katsanidou 2013) and replications are still not published
as much as they should (Carsey 2014), there is a growing debate on how
to make the discipline more open and reproducible. In the context of
this debate we discuss how graduate education in particular is an
interesting place for replications. The replication of a paper can guide
students during the transition from training to themselves undertaking
research. At the same time, graduate students are sufficiently
knowledgable to undertake a replication relatively independently. We
identify three key area in which we argue that replication can help
students (and teachers):

1.  familiarise students with cutting-edge research tools
2.  experience the practical difficulties of research work (statistical
    work)
3.  help produce a publishable paper.

In the sections below we will develop these ideas in some more detail.

Familiarise with research tools
-------------------------------

One of the key benefits of replications is that is introduces students
to current research and its practice. In many fields, the methodology is
rapidly evolving often as a result of more data and data analysis tools.

Computation environments such the R framework (R Core Team 2014) or
MatLab (2014) have greatly facilitated the development and
implementation of new methods in both qualitative and quantitative
research. Personally designed methods can be packaged and made publicly
available. This had lead to a large rise in the number of algorithms
being available, often written by the authors of the methods themselves.
However, non-commericial methods through which these software packages
are distributed, combined with the vast number of them, can make it a
somewhat daunting task determine the right software.

Replications generally concern published and peer-reviewed articles,
which means that the methods employed are proven to work and have also
undergone some review by the original author as well the reviewers. This
becomes especially useful when - as in most research - a combination of
different methods is required.

Many research focused platforms have emerge over the past few years
which can be very useful at the various stages of a research /
replication project.

Public repository website such as GitHub - or self-hosted open-source
equivalents such as GitLab or Gogs - offer a good place to host project
remotely. There are several key advantages to this:

-   a remote backup
-   a well documented and timed claim to the research idea
-   ability to work collaboratively on data analysis (e.g. .R files)

More recently, the rise of continuous integration tools such as Travil
CI, have created the additional advantage that code can continuously be
tested automatically. For a full discussion of continuous integration in
reproducible research see Fitzjohn ().

During the dat aanalysis phase, working with combinations of different
package can require quite some technical expertise, especially when a
combination of different packages is required. Q&A sites such as
stackoverflow - and more recently the ones based o the open-source
equivalent askbot, such as sagemath - allow users to post questions
which can be answered by experiences other users (who gain reputation).
In addition to solving the direct issue of user posting, experienced
users often offer other insights about interpretation of results,

-   Robustness to specification
-   -   computational simulations
-   data availability + bring home, make data available

Practical Difficulties of Research
----------------------------------

A good example is the replication of on the paper **Evaluating the
Nuclear Peace Hypothesis** (Rauchhaus 2009) done by Bell and Miller
(2013) provides an interesting example of how ....data
separation...problem stata....

Publish a paper
---------------

A finalised research project is only a first step towards a publishable
research paper. Following the example of the original paper, can help
with structure,

References
----------

Bell, Mark S, and Nicholas L Miller. 2013. “Questioning the Effect of
Nuclear Weapons on Conflict.” *Journal of Conflict Resolution*:
0022002713499718.

Carsey, Thomas M. 2014. “Making DA-RT a Reality.” *PS: Political Science
& Politics* 47 (01): 72–77.

FitzJohn, Rich, Matt Pennell, Amy Zanne, and Will Cornwell“Reproducible
Research Is Still a Challenge.”
<http://ropensci.org/blog/2014/06/09/reproducibility/>.

Gherghina, Sergiu, and Alexia Katsanidou. 2013. “Data Availability in
Political Science Journals.” *European Political Science*.

King, Gary. 1995. “Replication, Replication.” *PS: Political Science &
Politics* 28 (03): 444–452.

Mesquita, Bruce Bueno de, Nils Petter Gleditsch, Patrick James, Gary
King, Claire Metelits, James Lee Ray, Bruce Russett, Håvard Strand, and
Brandon Valeriano. 2003. “Symposium on Replication in International
Studies Research.” *International Studies Perspectives* 4 (1): 72–107.

R Core Team. 2014. *R: A Language and Environment for Statistical
Computing*. Vienna, Austria: R Foundation for Statistical Computing.
<http://www.R-project.org/>.

Rauchhaus, Robert. 2009. “Evaluating the Nuclear Peace Hypothesis a
Quantitative Approach.” *Journal of Conflict Resolution* 53 (2):
258–277.

Rich, Timothy S. 2013. “Publishing as a Graduate Student: A Quick and
(Hopefully) Painless Guide to Establishing Yourself as a Scholar.” *PS:
Political Science & Politics* 46 (02): 376–379.

The MathWorks, Inc. 2014. *MATLAB and Statistics Toolbox*. Natick,
Massachusetts, United States.
<http://www.mathworks.com/products/matlab/>.
