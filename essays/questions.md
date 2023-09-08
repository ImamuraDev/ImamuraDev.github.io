---
layout: essay
type: essay
title: "Asking the Right Questions"
# All dates must be YYYY-MM-DD format!
date: 2023-09-07
published: true
labels:
  - Software Engineering
  - Stack Overflow
---

<img width="200px" class="rounded float-start pe-4" src="../img/difficulty/degree_difficulty.jpg">

## Introduction

“How To Ask Questions The Smart Way,” by Eric Raymond, is a very long and certainly “interesting” read, filled with blunt and even self-admittedly rude statements about the way things should be done. It is an article that is roughly as old as I am, a fact reflected in both the antiquated and outdated terminology used throughout, as well as perhaps the frankly elitist views that he holds with regard to not annoying the ever-wise “gurus and experts” that make up the “hacker” community. My many gripes with the text notwithstanding, Raymond does manage to make a few fair points about the namesake of the article in-between constantly calling everyone a “luser.”
	
## What is a Smart Question?

According to Raymond, a smart question is one that first and foremost includes effort and detail on the asker’s part. One should never ask a question that can easily be answered by doing a simple google search, the bare minimum amount of effort one should put in (and honestly easier than going through the effort of posting and waiting for a response). He posits that you should furthermore search through the manuals, FAQs, and web in general before resorting to actually asking a question.

Once you actually determine that a question needs to be asked, you should choose the right place to post it, making sure that it’s within the bounds of the forum’s content. Ensure that you create a concise and accurate title to describe your problem, and also make sure to correctly tag the post with relevant languages, frameworks, and info. As for the actual body of the post, utilize proper grammar and syntax that is correctly formatted, and use formatting tools to correctly display code if necessary. Your description should be a precise (and chronological, if necessary) account of the issues that you are having, as well including details of the environment that it was encountered in (e.g. OS, settings, etc.). You should also include how you have already tried to troubleshoot the problem and how to reproduce the problem you are having locally. Raymond also advises that you refine your question such that it is explicit and not open-ended, so that there is less effort required on an answerer’s part and thus a higher chance they will actually answer, as well as to be careful not to ask yes or no questions, lest you risk an encounter with the apparently inherent sass of the internet and “hacker” community. Once you (hopefully) receive an answer, be sure to update your post with both thanks and credit to the solution.

## An Example of a Smart Question

For an example of a question asked right, at least by Raymond’s standards, we will take a trip to Stack Overflow, a site I’m sure needs no introduction. This question is entitled, “Why does my Kubernetes Cronjob pod get killed while executing?” First and foremost, they establish a clear question that describes their situation concisely. In the body of their question, they also begin by providing context for both the version of Kubernetes that they are working on, as well as going more in depth about their actual problem. They provide two sentences that give valuable context of the situation, describing the purpose of their code as well as what triggers their issues. It is also perfectly understandable and readable (even though there are a few grammar/syntax mistakes here and there).

They go on to provide relevant portions of their code as necessary, as well as detailing how their problem differs from other posts they have read, showcasing that they did their due diligence and still weren't able to come up with an answer. Conveniently for respondents, they also include logs which give further detail to the problems that they face.

Finally, they end their post with the specific troubles they have had in solving the issue and final notes, before courteously thanking anyone who is willing to help. Overall, not perfect but still a very well put together and detailed question, including context and effort. This quality seems to have paid off, as the following day they were answered by a similarly well-constructed reply that both thanked them for the helpful context they provided and also solved their issue.

## A “Not So Smart” Question

To be honest, you can likely tell what the issues are just by looking at the picture above. But for specificity’s sake, let us go over them. Obviously, it is hardly even coherent, with many grammatical errors throughout. It seems as though more text has been copy pasted from error logs as opposed to actually typed by the person. Even if one understands them, there is literally no context as to what they are working on besides the tag, and practically no way to assist them. This is reflected in the only response they have received so far: 


## Conclusion

While I may not agree with much of what Raymond says in his article, one good point that he does cover is how to write good questions. By providing context and details, being concise, accurate, and putting in the effort, you make your question much easier to answer, if not outright solving it yourself. In my personal experience, asking questions is hardly even necessary nowadays. With everyone so used to interconnectedness and having done so for so long, most questions that you will be asking have already been asked and answered, possibly numerous times across the web—granted, it depends on the obscurity and newness of your work, but nonetheless. Even so, it is important to understand how to ask smart questions, whether online or in-person, as you might one day have to do so. By following the guidelines, you can provide the necessary context and information to help others help you more effectively.

Link to “Smart” Question: https://stackoverflow.com/questions/68643381/why-does-my-kubernetes-cronjob-pod-get-killed-while-executing
Link to “Not So Smart” Question: https://stackoverflow.com/questions/77064518/how-to-solve-this-403-error-in-our-website
