From drab to fab
================
Mine Çetinkaya-Rundel and Maria Tackett
February 2020

In our September 2014 column titled we wrote about five concrete reasons
your students should be learning to analyze data in the reproducible
paradigm. One of the reasons we gave was that \`\`\[t\]his workflow
establishes the norm that data analysis and science in general should be
an iterative process". Just like data analysis in general, data
visualisation is also an interative process.

\[TODO: Better link\]

It can be very inspirational to share highly polished data
visualisations with students. A few of our favourite visualisations to
bring to the classroom are text analysis of Donald Trump’s tweets by
David Robinbson
([varianceexplained.org/r/trump-tweets](http://varianceexplained.org/r/trump-tweets/)),
the Dialect Survey by Joshua Katz
([joshkatz.co/dialect.html](http://joshkatz.co/dialect.html)), and map
of America’s weather related disasters by Tim Meko
([washingtonpost.com/graphics/2019/national/mapping-disasters](https://www.washingtonpost.com/graphics/2019/national/mapping-disasters)).
We also love the NY Times series What’s Going on in This Graph?
([nytimes.com/column/whats-going-on-in-this-graph](https://www.nytimes.com/column/whats-going-on-in-this-graph))
as well as just about any visualisation from the Flowing Data blog by
Nathan Yau ([flowingdata.com](https://flowingdata.com/)), The Pudding
([pudding.cool](https://pudding.cool/)) and The Functional Art blog by
Alberto Cairo
([thefunctionalart.com](http://www.thefunctionalart.com/)). For example,
the stories on how the American work day changed over 15 years
([flowingdata.com/2019/07/16/how-the-american-work-day-changed-in-15-years](https://flowingdata.com/2019/07/16/how-the-american-work-day-changed-in-15-years))
and on gender tropes in film with screen direction
([pudding.cool/2017/08/screen-direction](https://pudding.cool/2017/08/screen-direction))
both feature in-depth and enlightening but simple visualisations that
tell a meaningful story. We like these examples because their message is
clear enough to glean quickly, but one can extract deeper insights by
looking at them for a bit longer, a bit more closely.

All of these visualisations share one thing in common though – they are
incredibly polished. It is possible for a student just starting off to
think “well, I could never do that\!”. Or perhaps worse, to think that
they can, and not get to something as impressive on their first or
second try and get discouraged. We believe that it’s important to show
students not only the end result, but also the process of building a
meaningful data visualisation. This journey can be incredibly
educational in its own, as each step of the improvement is an
opportunity to teach a new data visualisation or wrangling technique.

In this column we walk through one such example. The data come from The
American Association of University Professors (AAUP), which is a
nonprofit membership association of faculty and other academic
professionals. In 2013, the AAUP published a report on Trends in
Instructional Staff Employment Status, which includes a visualisation
that looks like the following.

<div class="figure">

<img src="img/staff-employment.png" alt="Reproduction of visualisation included in the 2013 AAUP report on titled Trends in Instructional Staff Employment Status" width="1626" />

<p class="caption">

Reproduction of visualisation included in the 2013 AAUP report on titled
Trends in Instructional Staff Employment Status

</p>

</div>

The visualisation is a bit difficult to make sense of, and this is the
point. We show this visualisation to the students at the beginning of
the class, with some clarification on what the y-axis means (various
levels of staff at the university who teach classes, ranging from
graduate students to full-time tenured faculty) and ask them to
interpret the visualisation in teams. Eventually students are able to
identify the main message of the story: the highest proportion of
instructors are part-time faculty, and this proportion has been
increasing from 1975 to 2011. Along with this main message, students
also naturally come to the conclusion that this is not the best
visualisation of these data, and in fact, the visualisation makes it
hides the main message instead of making it loud and clear.

This report by the AAUP shows trends in instructional staff employees
between 1975 and 2011, and contains an image very similar to the one
given below.

## Further reading

1.  Joshua Katz, Dialect Survey - joshkatz.co/dialect.html

2.  David Robinson, Text analysis of Trump’s tweets confirms he writes
    only the (angrier) Android half -
    <http://varianceexplained.org/r/trump-tweets/>

3.