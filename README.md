# FlowSense

---

## Tech Stack

- **Frontend**: React
- **Backend**: Django
- **Database**: PostgreSQL

---

## Inspiration
During my internship, I worked on multiple projects that contained foreign concepts that needed to be acquired by reading long dull and complicated reports. As an overstimulated Gen-Z, my short attention span and inability to concentrate without Subway Surfers made this very difficult and time consuming. I realized that when learning about a foreign concept, 2 main problems come up:

1. Obtaining definitions of words is too tedious: Googling concepts lacks context, split screen with 
   ChatGPT includes context but takes up space on the screen, both are slow
2. After finding definitions, or taking breaks, it is not instantly recognizable what I’ve already read and 
    what I haven’t yet seen

This motivates the creation of FlowSense, a reading tool that is more interactive, visual, and assistive. It encourages the use of keyboard shortcuts while reading so that the eyes stay on the current sentence and do not wander to follow the mouse cursor.

## What it does
Flowsense provides interface for interacting with reports, with functionality to use an LLM API to define words in the context of the report and writing inline notes for future recollection and organization. It is all cleanly organized into tabs where PDF files can be added into the system, which processes them and keeps the source formatting so that there is no confusion with the original. 

## How we built it
We used a React.js frontend with Django for backend and a PostgreSQL database. It includes embedded OpenAI calls to GPT.

## Challenges we ran into
Formatting and highlighting sentences in PDFs is difficult since it is generally broken into lines instead. Also, importing the PDF files took some time because some of the modules have poor documentation that posed problems to work around.

## Accomplishments that we're proud of
We expected a huge time scramble so one of the main focuses was managing our time well so that the second night wouldn't have to be an all-nighter. Saturday ended up being very comfortable as we had our minimum viable product ready quite early in the day so the rest of the day was spent adding additional features with relatively low stress level. As a group of mostly beginners, this is something we can be proud of and means we can take more risks in future hackathons. Also, an easy way of getting through this project could be to have the users simply copy and paste text rather than upload PDFs but we deliberately chose the more difficult option because that is what would be more useful to users, and being able to preserve the initial report format was important to our design. This is something none of us had ever done before. Taking these kinds of calculated risks is also something we are proud of, as it boosts our confidence to take on new problems we have never tackled before. 

## What we learned
We learned that Hackathons are more of an opportunity to build on weak points rather than only divide work by giving each member something that is part of their strengths. Although for the most part each team member worked on something they knew already, a lot of teaching took place and gave room for us to develop new skills. In addition, we learned how our ideas going into the hackathon can change on the fly to adapt to feasability and utility. 

## What's next for FlowSense
Add social media features where you can see other users, a recommendation system for reports and users, and more features.

## Team
FlowSense was developed within a 36-hour period during Hack the 6ix 2024 by:

- Kenny Guo
- Dylan Nagel
- Simon Hampton
- Jason Sun

## Watch the Demo
Check out our demo video on YouTube to see FlowSense in action: [Watch the Demo](https://youtu.be/2c1xXcaIki8)
