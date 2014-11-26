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

For instance, when replicating the paper **Exploring temporal
relationships between scientific and technical fronts: a case of
biotechnology field** by Huang et al. (2014), the following packages
will be used:

-   iGraph (social networks)
-   tm (text mining)
-   RWeka (machine learning)

and their interactions.

Combinations of tools like these are very fertile in their utility
across disciplines and also methodologies. In this instance, **tm** is
used to mine text documents (research papers and patent applications),
after which **RWeka** is used to apply machine learning techniques to
this information. Finally, **iGraph** is used to map the social network
of these interactions.

-   computational simulations
-   data availability + bring home, make data available

Practical Difficulties of Research
----------------------------------

A good example is the replication of on the paper **Evaluating the
Nuclear Peace Hypothesis** (Rauchhaus 2009) done by Bell and Miller
(2013).

References
----------

Bell, Mark S, and Nicholas L Miller. 2013. “Questioning the Effect of
Nuclear Weapons on Conflict.” *Journal of Conflict Resolution*:
0022002713499718.

Carsey, Thomas M. 2014. “Making DA-RT a Reality.” *PS: Political Science
& Politics* 47 (01): 72–77.

Gherghina, Sergiu, and Alexia Katsanidou. 2013. “Data Availability in
Political Science Journals.” *European Political Science*.

Huang, Mu-Hsuan, Ssu-Han Chen, Chia-Ying Lin, and Dar-Zen Chen. 2014.
“Exploring Temporal Relationships Between Scientific and Technical
Fronts: a Case of Biotechnology Field.” *Scientometrics* 98 (2):
1085–1100.
doi:[10.1007/s11192-013-1054-0](http://dx.doi.org/10.1007/s11192-013-1054-0).
<http://dx.doi.org/10.1007/s11192-013-1054-0>.

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
