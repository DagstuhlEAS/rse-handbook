Copyright K. Kuksenok (@katerena) 2016

## Requirements Gathering 101

(Braindump mode!)

Making software requires making many small decisions, and the more explicit the design process, the fewer of these decisions are made based on implicit and undocumented assumptions. Any requirements gathering is better than none, so consider your answers to the following questions.

WHO will use the software? Be honest, specific, and as narrow as possible. Most likely the answer is you, six months from now, when you have forgotten why or how it works. Users include: your future self, anyone who is in a position to give you feedback or advice (supervisor, that one post-doc who's really good at Python, a distant collaborator), hypothetical future students who would need to understand the software enough to use it or to extend it.

WHERE is it, how does set-up work, if someone says "oh this is cool! can I try it on my data :D ?" what will you do? Will you need to do a lot of "cleaning up" to make your work presentable? Will you need to find a lot of auxillary files, or change hard-coded file paths, to make it packageable? Are there small things you can do *now* to reduce the amount of this kind of work *later?*

HOW will the software be used (move the stuff abotu users form "WHO" to here?) The more hypothetical and remote the users, the more you risk the danger of generalizing too soon, over-engineering, and feature-creep. Imagine concrete people and concrete scenarios, and prioritize feature inclusion and extensibility concerns based on that. Acknowledge that, realistically, the whole list of ideas will never be implemented, only some top-priority stuff. (something about MVP, some resources)

WHEN will the software be updated/changed/maintained? What kind of accomodations would you need to make to your typical work patterns to be able to do enough maintenance for the software to still be useful?
