# Personal Notes 

> Right now this is just a dump-all site for thoughts. Will later become a real README.

## Order of tests:

Meta-Ai, Chat-GPT, Claude, Gemini, Perplexity, Mistral 


## First Ideas

- ChatGPT, Claude and Gemini will work fine.
- Maybe there will be some issues due to the Acordo Ortografico.
- Portuguese Sentences are less difficult than Japanese. It wouldn't need as much tweaking as the Japanese teacher agent. Nor so many examples. 

---

# HOMEWORK - PREWEEK (DRAFT): 

## Github Link to Sentence Constructor
https://github.com/candytale55/free-genai-bootcamp-2025/tree/main/sentence-constructor

## Github Link to GenAI Architecture


## Hypothesis and Technical Uncertainty*




## Technical Exploration*
_Briefly describe the path of technical exploration during these projects._



## Final Outcomes*
_Describe your final outcomes or domain knowledge acquired._


## Considerations / Exceptions / Accommodations
_If you want to add anything additional to share with your instructor. Or if you're submitting late and you want to request an exception or considerations._


---




## Additional Notes

### Acordo Ortografico

The Acordo Ortográfico da Língua Portuguesa (Portuguese Language Orthographic Agreement) is a set of rules created to unify the spelling of Portuguese. The goal was to make reading and writing easier and consistent in Portuguese speaking countries. It removed some silent letters, simplify accents, and fixed small spelling differences between countries. It was signed in 1990, but different countries started using it at different times. 

For large language models (LLMs), that are trained on huge amounts of text from books, websites, and other sources — some written before the agreement and some after, this means that the model might mix old and new spellings or use the spelling from one country more than another. 

This means that when using Portuguese with an LLM, it helps to say which version or country’s spelling you prefer, especially if consistent spelling is important.

I've experienced this issue with ChatGPT before the boodcamp, so I expect this could happen if not addressed. 


###  Draft for Sentence Constructor Tester

```
I wan't to test the answer given to this prompt.  This are the items to test:

Things to test:
Assistant must use European Portuguese all along, regardless of the language the student is communicating in.
Must provide a vocabulary table: 
* Must contain the main vocabulary (dictionary form only). Do not include articles, pronouns, or prepositions — the student must figure those out.
* Verbs shouldn't be conjugated (dictionary form only).
* Nouns should not have nominal inflection (dictionary form only).
* It's ok to include two word options, but only if both words are just as commonly use. 

Must offer clues about possible sentence structure:
- Should not give a schema of the sentence structure.  Only give hints when the structure in Portuguese is particularly special.
- Encouraging the student to think through conjugations and word order. But do not provide examples that are easy to replicate.
- When offering clues about possible sentence structure, **never use the exact verbs from the student's sentence** — use other common verbs as examples.
- Do NOT give away the full translation, even if asked.

When the student gives a translation, provide feedback:
- Point out what’s correct and natural.
- If the sentence has mistakes the user should know at his level, provide more hints so that the Student can try a second time. 
- Suggest improvements or alternatives when necessary.

Sentences must be:
* In European Portuguese
* Suitable for the student's level indicated.
* Would be commonly used by native speakers in everyday life.
* Must not use old spelling (before the Portuguese Language Orthographic Agreement)

Please evaluate the prompt response and give a numeric score that is easy to replicate with similar prompts and that is consistent.
Explain why you chose the score.
```

## Notes about Videos (TODOs)

### Pre-Week (REWATCH)

https://app.exampro.co/student/material/exp-genai/8052
https://www.youtube.com/watch?v=_r1X380nEKg 
28.00 - Asking for help. Reporting Errors
40.00 - SheClouds, SheGenies, GenAI-Español

46.00 - ML104: Architecting GenAI systems WATCH

1.03.00 - Architecting GenAI - Conceptual, Logical and Physical. (Also TOGAF, C4 model)
Business Goals & Designs Patters
1:13 - Repo instructions (Create your own Repo)  
1:15 - Diagram of LangPortal App (BackEnd and FrontEnd) 
       Used Windsurf
1:20 - Logical View
1:28 - Conceptual Design (Start from here)
1:39 - Discussion on database
1.41 - Gen AI Magic. WATCH
1.55 - Make a Conceptual Diagram INSTRUCTIONS


### Week 1 -  (REWATCH)

## Week 1 - Dev and DevTools

https://app.exampro.co/student/material/exp-genai/8065 
https://www.youtube.com/watch?v=F_aMu_0V_3c

10.00 - What this is going to be about.
	Backend - Lang Portal
        Coding Assistant: Cursor, Windsurf, etc
	LRS (Learning Record Store)
	SQL3
21:00 Download the BackEnd Code


Add. Cursor AI Lab (GenAi Essentials)
https://app.exampro.co/student/material/exp-genai-001/7938
https://www.youtube.com/watch?v=QOWxXmyIiQ0



