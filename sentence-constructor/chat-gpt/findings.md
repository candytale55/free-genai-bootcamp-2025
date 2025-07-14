# chat-gpt findings.md

## Which Model:

Using bpth the free-tier Chat-GPT and chatGPT-Plus (until it reaches its limit).


## Prompting Guides:
Prompt engineering best-practices from ChatGPT: 
https://help.openai.com/en/articles/10032626-prompt-engineering-best-practices-for-chatgpt

---
---




## Compare P.00 vs Alt.P.00 Prompts Update
(2025.07.14)

I still need to make a serious comparison using scores and a fixed system, but in general, the version suggested by ChatGPT worked the same or better than the one in prompt.md. I think this may be because Portuguese is not as hard as Japanese.

Truthfully, I don't want to dwell too much on this point. I want to keep moving forward, testing other LLM assistants, and progressing to the next stages of the bootcamp.

What I will do is add a good enough example to Alt.P.01 and work from there.


### So, future wish TODO list:

- Test each prompt test in both chats and rate them.
- I wrote a draft for a test but haven't implemented it. Keep it in my personal notes (note to self: go search for it when you can). I have no idea how to test prompts properly, which is why I'm skipping this for now and leaving it for later.



## Compare P.00 vs Alt.P.00 Prompts
(2025.07.10) 
> Testing the two prompt options with the same sentences to see which one works better. 
- **Why?:** I think that the changes proposed in the Bootcamp are overkill when dealing with Portuguese (from a Spanish speaker student perspective) and the prompt P.00 with examples is actually getting worse results than the simpler Alt.P.00 prompt suggested by Chat-GPT. 
- **TODO:** After testing is done, don't forget to re-check the formatting parts at minute 12:00, 17:45, 22:00 (examples of structures), 24:00, 29:30-33:00 (NA for PT, but cool!), 31:00 to improve the final prompt.
- Specially examples at 40:00.
https://app.exampro.co/student/material/exp-genai/8055 


### Alt-P.00 Alt-Chat-GPT Sentence Constructor Prompt
> Suggested by ChatGPT in chat (bottom): 
https://chatgpt.com/c/686f6581-ae90-8013-a4c2-140f8a7e833c 
> To be tested along prompt.md 
> Doesn't have examples so far. 

Note to self: Check the tests by Ctrl + F " Tenta agora reformular a frase com essas correções. Estou a torcer por ti!" - They are not the first sentence I tried. 


### Chat-GPT link: 
https://chatgpt.com/c/686f7691-1994-8013-b415-fbcd1807f7e5
(2025.07.10)

### Results:
* GOOD: 
    - Fairly good results. Very similar to P.OO prompt below (the one copied from Meta-Ai)
    - Didn't give the answers away. The hints use other verbs/words examples.  
    - Hints are useful to guide the user into constructing the sentence.

* BAD: 
    - Nothing to report on first try. Need to test it and compare results.

* TO-DO: 
    - Keep in mind: I feel like the hints are too easy for a Spanish native speaker. But for an English native speakers they may work very good. (What I feel to easy is probably because of my native tongue and the assistant is actually doing a good job). 

---

### P.00 Chat-GPT Sentence Constructor 
> Copied from Meta-Ai Sentence Constructor
> Starting point (Prompt 0)


### Chat-GPT link: 
https://chatgpt.com/c/686f6581-ae90-8013-a4c2-140f8a7e833c
(2025.07.10)

### Results:
* GOOD: 
    - Fairly good results.
    - Keeps writing in Portuguese, even when the student writes in English.
    - Vocabulary provided is adequate for the sentence. 
    - Hints are useful to guide the user into constructing the sentence. 
        * Two of the three hints are adequate and don't disclose the answer. 
* BAD: 
    - The first hint: "_A primeira parte é uma oração condicional (algo do tipo: “Se fores à…”)._" is giving the conjugated verb away (_fores_).

* TO-DO:
    - There might be two ways of constructing this phrase. I was thinking of using an _infinitivo pessoal_ because that's what I was learning in class and according to my teacher in European Portuguese people prefer it instead of the Conditional (which is also correct). However the assistant states it's the other way around. **I suspect HALLUCINATION**.
    - The examples are too long and I don't feel happy about them. Better examples should be included, probably.

