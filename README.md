# Gender bias in the danish job market
In this project, I have analyzed whether there is evidence of gender bias in job postings in the danish job market. More specifically, I have scraped and analyzed around 900 job texts and applied an algorithm to search for evidence of gender bias in these texts. 

## Gender, words and job texts
We hear it all the time. There is a need for more women in more technical fields such as finance and IT. Not only do we need more women in these fields to get a more equal distribution of gender. We also need more women simply due to the rising demand of people with technical compentences. 

Why then, are women underrepresented in these fields? I don't think there are any clear answer to this, but there are some patterns that are interesting to examine. One such pattern is the dominant discourse sorrounding different fields. Think of how you would describe the qualities needed for a HR-role versus a IT-role. HR is often spoken of in "softer" terms while IT is spoken of in "harder" terms. Suprisingly, we also see many more women in HR than in IT. 

Research has shown that certain words are more appearant in job postings in male dominated fields and female dominated fields (such as IT). These words are referred to as "masculine words" and "feminine words" and typically describe the qualities needed in candidates. Furthermore, research has shown that women may find jobs less attractive and find themselves less qualified for jobs if masculine words appear (frequently) in job postings. This may explain some of the gender equality in male dominated fields such as IT. If masculine words appear frequently within job postings in such fields it may deter women from applying to jobs.

I decided to examine whether this was the case in the danish job market. I designed an algorithm to scan texts for appearances of masculine and feminine words, how frequently they appear and where in the text they appear. The masculine/feminine list of words are based on research into such words in english and translated into danish.

The results? Well, see for yourself in the notebook.
