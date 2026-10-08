# Learning Impact Snapshot

**Live page:** https://hareemmasood40.github.io/learning-impact-snapshot/

A one-page learning insights report that asks the question every learning leader cares about:
**is the training actually working?**

It uses six months of learning data from *Northbank Retail*, a **fictional** company with 1,200
staff across 24 stores. I created the example data to practise this kind of analysis. It is not
real company or employee data.

## What the report looks at

1. **Completion vs use on the job.** 57% of staff finished the pathway, but only 34% were seen
   using the new skill in a manager check-in.
2. **Where learners drop off.** One module, a 42-minute video, lost 22% of the learners still
   going. No other module lost more than 7%.
3. **Course length.** Across 140 courses, completion falls from 82% for courses under 10 minutes
   to 41% for courses over 20 minutes.
4. **Learning and customer satisfaction.** Stores with higher completion saw bigger rises in
   customer satisfaction (correlation 0.73). That is a strong link but not proof, so the report
   suggests a randomised half-and-half rollout to test it fairly.

It finishes with three practical recommendations.

## How it was built

- I chose the questions a learning leader would ask, then worked with Claude (AI) to create
  realistic example data, analyse it and build the page.
- Charts are hand-drawn SVG in plain JavaScript (no chart library), with hover details and a
  "Show the numbers" table under each chart.
- Works on phones and in light and dark mode.

## About me

I taught maths for over five years and I'm now moving into data and AI.
[LinkedIn](https://www.linkedin.com/in/hareem-masood-ai) ·
[More projects](https://github.com/hareemmasood40)
