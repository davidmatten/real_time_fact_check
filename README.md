# real_time_fact_check
A project to detect truth in real time.

Idea is around detecting non-truth in real time. Possible use cases include real time speech feedback. Imagine a politician saying: "I have never stood for tax cuts", and this could go through text to speach, be searched for contradiction against a body of their previous public speeches, and any counter examples of them saying "I support tax cuts" given in real time. Would be great to play the counter evidence video, or show the newspaper article, etc., live as they are talking.

This project has largely two components:
- Voice to text (NLP)
- Text search to find counter examples.

It is expected that the difficult parts would be
- Limiting search domain to only the person talking. Might have to build databases of videos / articles with tag's. Pre-processing would be most efficient for real time result giving.
- Finding logical contradictions within language.
