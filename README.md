# ~~why-archived~~

- <s>there is no such thing as cljctools, it's an attempt to "hold",control,make an org, rather than value
- so we as makers/contirbutors have our namespaces, so when should it be project and when ours?
- well, it's always one thing we're making that defines the namespaces, other derivative tools share it
- for example, https://github.com/DeathStarGame/DeathStarGame should have it's own namespace, because it's a living thing, not abstract "some games"
- same with clojure/clojure itself for example - all other tools share /clojure namespaces, making it clear - we're complimentary things for the value, not an org
- why I started cljctools? because of `mult` - a very conrete tool, an extension; and I was afraid to put inot my own namespace, the "big-organizer" took over and I dropped cljctools - "hey, I'm gonna replace the Internet with one namepsace"...
- people make tools, no one holds one namepsace for that
- and if some project is it's won thing, it should have a mirror namepsace - DeathStarGame/DeathStarGame, clojure/clojure or even mult/mult
- so properly, I should have dropped mult/mult namepsace
- but, we're people and making tools as part of our own namepsace is ok as well, so it can be /user/mult
- so which one should it be? I think user namespace, as it's a tool, forkable, and cljctools/cljctools should got to user as well
- and the project - DeathStarGame/DeathStarGame - can have such tools as a dependency, linked to one of the forks
- the same thing happened with making a YT channel for DeathStarGame/DeathStarGame - which, again , was an fear-induced attempt of "holding" the internet
- did resolve it yesterday - https://github.com/DeathStarGame/DeathStarGame/commit/c712c6cea43a2ad4f9579f529ea29bc14f38f793 - both helping the project nad myself
- takeaway - focus on creating value, not abstract organizations
- if a repo is a living its own project, it should get its mirror namepsace - /repo/repo</s>

UPDATE (same day):
- I'm wrong. I need that namespace both to avoid collisions and because it's dream
- don't know, probably moment of weekness/disbelief...
- I do apologize for mischievous post

[same post on reddit](https://www.reddit.com/r/Clojure/comments/jp1snq/githubcomcljctools_archived_will_use_usernametool/)  
[same post in deathstar.lab](https://github.com/sergeiudris/deathstar.lab/blob/50943c8286ed2c9d2506dc2a0c73c5961ef92fd9/posts/2020-11-06-cljctools-archived.md)
