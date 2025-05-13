# CodeDay Memetics Internship

> In the tech industry, we publicly study & document security vulnerabilities. We reward white hat hackers who disclose their work for the public benefit. This transparency helps good actors coordinate on defensive strategies. 
>
> **Human minds can be “hacked” through narratives, and we have no coordinated defenses.**
> 
> — [Open Memetics R&D Grant Proposal](https://docs.google.com/document/d/1kCLMHYjgWRPCjL5d7qXmN1QzgNXHmuljULaZg_04pZI/edit?tab=t.0)

This is a summer [CodeDay](https://codeday.org/) internship. The goal is for you to make a novel contribution to the emerging field of "open memetics". There is a LOT of low hanging fruit that may have very high impact for society, but that no one is working on, for various reasons. This is the gap we're here to fill. 

The broad categories of the work are:

- **Tooling** — creating open source tools that can track the spread & evolution of narratives in a given network (basically open source versions of things like [Graphika](https://graphika.com/)), tools for transparency & coordination, for surfacing information that people want surfaced  
- **Analysis & research** — finding & answering open questions, and creating predictive models of how things spread in culture, and what they do to the underlying "memetic topography". 
- **Outreach** — actually using these tools in real communities & cultures that you belong to. Ideally create something that can go viral that acts as a way of collecting data & spreading awareness of this work. 

## Project ideas

**(1) Bluesky app to semantically cluster all replies to a given thread** 

[Treeverse](https://github.com/paulgb/Treeverse) is an app that can take any post on Bluesky and visualize all replies in a tree format. What we want is something very similar, except displaying the replies semantically clustered. 

<img src="https://github.com/user-attachments/assets/529f7691-32aa-4ce6-bd3b-c42cac74bf19" width=450>

What this will do is reveal "the shape" of the discourse. When a politician or a journalist posts something and gets thousands of replies, usually they all fall into a few "buckets" (people tend to say the same thing over & over). This tool will help surface novel ideas, and potentially coordinated bot activity.  

**(2) Implement "view source" on an idea to see its history in a given network**

As [described in this viral tweet](https://x.com/DefenderOfBasic/status/1868816060599955560), this is a fairly simple prototype that doesn't yet exist. Can use the Twitter Community Archive dataset https://www.community-archive.org/.

We should be able to describe any idea (like "memetics, the study of how ideas spread, propaganda & narratives") and use semantic search to show (1) the earliest occurence of this idea (2) a graph of how discussion around it rises & falls over time (3) bonus point, add emotional sentiment, to see if the sentiment around the idea changes over time.

Can also try it on bluesky datasets as a control group. 

## Background reading

- [How we crowdsourced 5 million tweets](https://omarshehata.substack.com/p/twitter-shut-off-api-access-users) and the long term vision of that project.

See especially the [attributes & language API](https://developers.perspectiveapi.com/s/about-the-api-attributes-and-languages?language=en_US#bridging) that [Andy_Matuschak](https://x.com/andy_matuschak/status/1780739603617739234) discussed wanting to see someone prototype (no one has yet!!!)

- [The Neighborhood Map & Virtual Feeds](https://alexpacheco.substack.com/p/filtering-the-information-network) - on a better way to find information on social media that can completely change the nature of how ideas spread

> Propagandists will also be disrupted as targeting methods will have changed. Decentralizing the network makes their messaging increasingly inefficient and they’ll have to expand their number of operators for wider presence in more niche neighborhoods. But in neighborhoods where more people know each other, visitors and other foreign actors are put at a disadvantage

- [University of Zurich unauthorized experiment on reddit scandal](https://www.newscientist.com/article/2478336-reddit-users-were-subjected-to-ai-powered-experiment-without-consent/) - this is significant because they were trying to do the same thing we are trying to do, but they treated people as subjects, instead of active participants in the research. In our paradigm, the subject must themselves be aware that they are being studied, they have to choose to participate, because they WANT to answer the question/because the answer matters to them.

## Side quests / positive externalities 

These are additional goals that are not projects in themselves but would be a very valuable secondary goal to accomplish.

- **Write down a "beginner's guide to open source memetics"** - keep track of all the resources that were useful to you, including technical ones like good libraries to use for semantic embeddings/sentiment analysis, as well as theoratical/big picture vision. This acts as a way to show your work to future employers, and pave the way for future contributors to this field
