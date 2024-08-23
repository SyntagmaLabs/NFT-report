These are the notes of the working group implementing **NFT mechanics report 2022**. The research process is organized as iterative development of a note collection in a Zettelkasten-like structure using github and [Obsidian](https://obsidian.md/).

## General principles
1. **One note — one atom**. It can be project description, a source summary, or one complete thought. A note represents a minimal complete unit of thinking. It is very important because all the cool network effects come from links, and with fuzzy items, these are confusing.
2. **Blockchain of thought**. Think and work in threads. If you're going through the notes and have a new thought, create a new note for that thought and link the two notes together. If you have a thought that doesn't follow from any of the previous discussions, start a new thread from a registry note. Details below.
3. **No orphans**. Always connect notes with links.
4. **Let's make the best rules**. Please try to follow the process and the rules outlined below. If something doesn't make sense or turns out frustrating when you do the work, rather than silently sabotaging the rule (or yourself), please, raise an issue, and let's switch it out. This is experimental tech, no one really knows the optimal configuration (yet).

## How it works
We use eight kinds of notes. Don't worry, it will make sense (one day).
1. **Thought note**. Represents a unit of thinking about a thing (whatever that is). It should have one clear point, have an inbound link from the previous thought, and be rather clear on what it says. 
	* Try to have the summary in one sentence as the note title (in the filename). 
	* Use hashtag \#permanent at the end. 
2. **Source note**. Summarizes the (relevant) content of a source. Other notes **never** reference sources, but **always** reference source notes.
	* Use the structure from [[0rg — minimal viable source note]].
	* Use hashtag \#source at the end. 
3. **Project note**. Talks about a project. Describes all of the functionality of the project. Categorized projects are listed in the corresponding registry. Uncategorized projects can be found by looking at the project nodes connected to the hashtag, but not anything else.
    * If the project has functions cloned from another project, make a link to the note about that other project (e.g. "has [[Compound (project)|Compound]]-like pools, called w\\e"). 
    * If there is a spin on the mechanism, create a **link note** (see below) and reference through it.
	* Use the structure from [[0rg — minimal viable project note]]
	* Use hashtag \#project at the end. 
4. **Link note**. Links two items in a meaningful way that deserves its own elaboration. There are two core use cases for this:
	1. **You had a shower thought connecting threads**. *What if leveraged debt positions and shitcoin farming pools really serve the same market need*. Create a link note that references all of the corresponding notes and explains the thought / the connection. The direction of links is up to you.
	2. **A pattern emerges**. Several constructions look like variations on the same idea (e.g. tokenized pooling, as discussed in Redefine 2020). Create a link note connected to the respective projects/patterns/thoughts. In it, explain the connection.
	* Use hashtag \#link. 
5. **Registry note**. Contains links to notes that list projects or start thought threads. Can have sections (if items can be grouped), can have paragraphs explaining the classification. Keep these minimal though.
	* May have a maintainer **and** an inbox section for stuff that probably belongs here. If there's no maintainer, and you need to add something to the inbox, look for a registry note above this one (closer to the root of evil), until you find a registry with a maintainer. This is important because of principle 1 and rule 1.
	* EVERY Thought and Project should be connected to a registry or to a chain of thoughts that traces back to a registry.
	* Use hashtag \#registry.
6. **Fleeting note**. Contains random half-baked thoughts that you had in passing and couldn't complete at the time. **Allocate time to clean those up**.
	* **Must** be listed in **your own** fleeting registry. 
	* **Must** have the hashtag \#fleeting (this is super important so that other people can exclude half-baked things from the graph by hashtag).
	* Please try to write a good summary as filename.
	* Please link it to all relevant notes. We maximize the chance that it ignites someone else to think about this.
	* You can refer to other people's fleeting notes. But please try and make an effort -- if you're getting somewhere with the thought train -- to make a **thought note** instead and link it to a proper registry or other thought note.
	* **Allocate time to clean up your fleeting notes**.
7. **Stub project note**. If you're writing about something and make a reference to a project that's not in the knowledge base yet, create a new note for that. BUT don't just leave it hanging:
    * Do a proper project note if you can.
    * If not, write a message in a corresponding inbox (see the bullet on registry notes above), linking the stub note there.
    * Don't use hashtag \#project.
    * Do use hashtag \#stub_project.
    * If you're turning a stub project note into a proper one,
		* Make sure to comply with the format [[0rg — minimal viable project note]]
		* Update the hashtags.
8. **Personal note**. A page about a contributor. Serves two purposes: 
	1. Anchor personal inbox
	2. Anchor personal fleeting notes.
	* All personal notes are listed in the personal registry, together with initials.
	* Use hashtag \#personal.

Always sign notes (see rule 1.3 below).

Take time to read/skim other people's notes and trains of thought. You might have a thought of your own or see a connection. Use graph view for that. If you see something wrong/confusing in the core body of work **and** it feels important, ask people to elaborate / cleanup.

## Collaboration rules
1. **Do, or do not. There is no try**. Always contribute to the main body of work in complete notes. A complete note is:
	1. One thought / one project (or product, for big projects) / one source. For projects and sources, see minimal viable definitions here, respectively: [[0rg — minimal viable project note|project]] / [[0rg — minimal viable source note|source]].
	2. Properly linked to its category. If it's a thought, either it is linked in its predecessor, or (if it's new) it is linked in the thread registry. Sources are hashtagged \#source. Projects are *always* linked in the project registry.
	3. Signed with your initials and date (e.g.: `AB, Aug 27, 2021`). If your contribution is a significant rewrite of a pre-existing node, chain your signature to what's in there already (e.g.: `AB, Aug 25, 2021 / Re: AB, Aug 27, 2021`).
	4. If your change to another note is minor (you wrote a new note and added a link to it in another note), re-signing the changed note is optional.
2. **Process your inbox twice a week**. You will get notes with new materials and/or requests, if you do, decide/process, and let people know.
3. **Process your section inbox twice a week**. If you're maintaining something, don't let the inbox of that section get too big.
4. **Keep your internal WIPs separate**. The main body of work has to be perfect and fully compliant with everything, as we're trying to get more people to co-exist efficiently. 
5. **Try to avoid note renaming, when possible**. Obsidian, of course, handles renames correctly (i.e. if you change a note's name, all of the links to it will get updated), but this can get ugly between commits. If you need to do it, let people know.
6. **Commit and push often** (except where such action would conflict with the First Law). We'll try to keep the mess and work order overlaps to a minimum, but some toe-stepping is inevitable. Frequent pushes and fetches help control that a bit further.
7. **Don't use hashtags aside from the ones defined above**. We might add some more (and might use them for classification of things later), but this will be a decision of the editorial board (or the benevolent dictator, whatever we end up having).
## Obsidian-specific notes
1. **Embed pictures, link files**. We don't want to store files on github, but pics are ok.
2. **Change Obsidian settings to save Attachments to Attachments/ folder**. Kindly rename the pictures you embed to something readable.
3. **Link/store pdfs**. If it's a pdf article, link both the surrounding page (e.g. arxiv) and pdf. If there are any doubts that the pdf may not persist (e.g. it's not on arxiv), kindly reupload the pdf to [our google drive](https://drive.google.com/drive/u/1/folders/1JN2SrWt-spVmztM3K0gXLxO97FZIoCw9).
