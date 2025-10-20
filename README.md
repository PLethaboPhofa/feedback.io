2025/10/09
1. Would be nice to get supabase up and running
    - Since supabase is unauthed, I need a captha system and cloudflare to protect myself against ddos and script kiddies

2025/10/13
1. Would be nice to get supabase integration complete
    a. This would include login and login considerations
2. I will likely get inspire images today, so I will integrate those graphics into the login page
3. Will have to continue this work over the weekend

2025/10/14
1. Complete supabase integration
 a. Including login
Stretch
3. Captchas too?

2025/10/15
1. Landing page
    - Relevant scientific literature section --> Include the research into what women see
2. Simple home page which aggregates feedback related to you

2025/10/16
1. Inspire work

2025/10/17
1. Do the weekly meeting then get back to feedback.io

UX
- https://gemini.google.com/app/da39e99e39577cab
- Word Count

UI
    - I dont have a theme, or any UI philosophy yet, please generate a page for collecting free form feedback, it should also include a thumb up button and a thumb down button, also a submit button

Features
- Insights are available once a month, like youtube highlights, you also get one per year.
- Timeline
    - Horizontal which is aggregated ( 1 day, total results)
    - Thumbs 
    - Feedback
    - Vertical view which is social feed
- Word cloud
- Insights 
    -> Summary
    -> Repeated themes
    -> Ratings ( thumb up, thumb down) 
- Verification
    - Captcha for anonynous login
    - No captcha for real login
    - Store feedback cookie, that prevents repeated feedback
    - Date field and user agent marks when feedback came in so we can filter out fake reviews, also store location if possible

FAQs
- Why? When two or more people report the same thing about you, even years apart, that thing is likely true
    I want to help people ground their peceprions about themselves in reality by harnessing the wisdom of the crowd
- What if I get no feedback, no feedback is feedback,
- Why wouldn't I  solicit feedback directly ( its not anonymous, its not asynchronous, its not persistent, its not analysed, let us take care of all of that for you, free forever also When multiple independent observers (or data sources) provide noisy signals about some underlying truth, aggregating those signals can yield a much more accurate estimate of that truth than any single signal on its own.)
Who? Anyone interested in their perfomance in interactions, perfomance meaning delivering clarity and satisfation, mostly independent contractors.
What? An anonymous feedback collection, persistance, analysis and presentation platform
When? Instantly, send a link collect feedback, 2 clicks ( unless you tpe)
Where? Social channels, QR codes for in place rating
Why? You perception of reality is as good as your ability to tell when someone is lying, scientifically, it has been proven to be non existannt
How? 
    Feedback is collected anonymously
    Analysed using Interrater reliability ( ), 
    Trend analysis, Topic clustering, Sentiment analysis,
    Outlier detection,
    Correlation mapping ( People who rate you high on “clarity” also tend to rate you high on “trustworthiness.” ??? Reinhard et al. (2011): Clear, fluent communication increases perceived honesty and competence.)
    Stability of traits
    Perceived trait confidence ( The probability that a reported behavior reflects reality, based on how often it independently appears)
If the system is anonymous why should I login in

Banger of a gpt conversation: https://chatgpt.com/g/g-p-68e7743ef100819181e6c5ef2a5534f2-feedback-io/c/68e77a2d-94c4-832b-964a-f70cb36d5afe

- In future
    - Proudly share you rating publically, show people how highly you are rated!

- For chat gpt later
Would you like me to outline a data model and algorithmic approach (e.g., how to mathematically combine multiple anonymous reports into a “truth probability” score)? It could help make your concept more concrete. -> Do this