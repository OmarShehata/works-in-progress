# Code Day Open Memetics Internship - Week Two

Last week we worked on clearly defining the scope of our projects, and learned about dimensionality reduction. The two main projects are (1) Angela working on a web app that can generate 2D "idea maps" from a live data source (2) Michael working on a way to detect "psyops" (coordinated & sudden changes in language, given a specific corpus like the Twitter Archives).

This week the goal is to make concrete progress towards an MVP of each project.

### Deliverables

1. **Generate a Nomic Atlas map** (Angela) - at https://www.nomic.ai/. This should be fairly simple, they have a Python API to generate embeddings, and add them to an atlas. See: https://docs.nomic.ai/atlas/embeddings-and-retrieval/generate-embeddings

Can try to take a set of tweets, or a list of emojis, or the image from the Alex Avilla video https://github.com/DefenderOfBasic/works-in-progress/issues/63

2. **Recreate the psyop/vibe graph** (Michael) for one or more users. Then see if you can write a script to "detect" a change like this. Can basically count words per interval (day, or month) and then scan for deltas. 

### Recommended reading

- [Mapping the Mind of a Large Language Model](https://www.anthropic.com/research/mapping-mind-language-model) from May 2024, this "the first ever detailed look inside a modern, production-grade large language model". Almost like a kind of "MRI scan for the minds of LLMs". This is basically a more sophisticated version of what we're trying to do with the visualizations of embedding, which let us take a look at "the mind of culture"
- A lot of people this week are talking about [Neuronopedia](https://www.neuronpedia.org/) which is a significantly more complex interface, I can't quite figure it out yet. If someone does figure it out and can explain it in layman terms it would be very useful.
- Read my writeup behind [good & evil words](https://github.com/DefenderOfBasic/good-and-evil-concepts?tab=readme-ov-file#what-do-these-distances-mean), for what I was trying to convey with this kind of interface, and why an interactive web tool that also collects data from users can reveal novel information about culture that we don't currently yet have.
