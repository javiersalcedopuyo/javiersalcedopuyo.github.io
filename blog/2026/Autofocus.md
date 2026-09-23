## Autofocus.md

For almost a decade I've been experimenting with productivity and task management systems and frameworks.
I've used post-its, paper planners, [bullet journals](https://bulletjournal.com/), [Kanban boards](https://en.wikipedia.org/wiki/Kanban_board), a super complex [Notion "second brain"](https://aliabdaal.com/newsletter/building-a-second-brain/)...

I'm in a very privileged position where my job allows me to pretty much work on whatever I want most of the time. That sounds great but it can be challenging if you are fresh out of school, or have only worked for corporations with very strict structures and processes. It takes discipline and good organisation skills.
That "evolutionary pressure" got a bit out of control and made me a sort of productivity junkie. I listened to podcasts, I read books, and I kept chasing the ultimate productivity framework.
To be honest, I was just procrastinating, but I convinced myself that I was ["sharpening the axe"](https://quoteinvestigator.com/2014/03/29/sharp-axe/). And also, the maintenance of the complex webs of notes, and wiki pages, etc became so complex that it required more time and effort than what I was saving: Adding a new task to the list required multiple steps and filling up a whole form of tags, dates, and other useless metadata.
I was basically reinventing bureaucracy from first principles.

In recent years I've been walking the way back, simplifying my system more and more.
Eventually I refined a very simple, very *low maintenance* system, that I've been happily using for over a year now.

Then, the other day, this wonderful [blog post](https://www.artofmanliness.com/character/self-improvement/autofocus-the-productivity-system-that-treats-your-to-do-list-like-a-river/) popped up in my [RSS reader](https://netnewswire.com/) (still a thing, still awesome!) talking about the [Autofocus](http://markforster.squarespace.com/autofocus-system/) task management system, created by the late [Mark Foster](http://markforster.squarespace.com/). The similarity with my current system was a bit uncanny, so I thought I might be onto something with it and I should write it down.

### Autofocus
For reference, here's a quick summary of *Autofocus* directly from [Mark Foster's article](http://markforster.squarespace.com/autofocus-system/):
> The system consists of one long list of everything that you have to do, written in a ruled notebook (25-35 lines to a page ideal). As you think of new items, add them to the end of the list. You work through the list one page at a time in the following manner:
> 
> 1. Read quickly through all the items on the page without taking action on any of them.
> 2. Go through the page more slowly looking at the items in order until one stands out for you.
> 3. Work on that item for as long as you feel like doing so
> 4. Cross the item off the list, and re-enter it at the end of the list if you haven’t finished it
> 5. Continue going round the same page in the same way. Don’t move onto the next page until you complete a pass of the page without any item standing out
> 6. Move onto the next page and repeat the process
> 7. If you go to a page and no item stands out for you on your first pass through it, then all the outstanding items on that page are dismissed without re-entering them. (N.B. This does not apply to the final page, on which you are still writing items). Use a highlighter to mark dismissed items.
> 8. Once you’ve finished with the final page, re-start at the first page that is still active.

### My system
The main differences with Mr. Foster's system are:
- Instead of a physical notebook, I use a `tasks.md` markdown file. That means there're no pages, and no real need to re-enter tasks. At work I have a single big one. For personal projects I have one per project. I do not use it for "life stuff", a simple to-do app does the trick for me in that case.
- I do a pre-pass of the inbox the day before, and keep a separated mini-list for each day. This allows me to reduce decision fatigue, start the day in "auto-pilot", and keep a record of what I've worked on each day (useful for stand-ups and sync meetings). This way I can also keep the inbox small, and see what I'm working on at a glance.
- Using the power of Obsidian (or any other markdown editor that supports wikilinks really), I can link to more detailed notes for *big* tasks.
- At the moment I don't have a system to determine when to drop or delegate a task.

The `tasks.md` file is always pinned on a side panel, and looks like this:
```
// tasks.md
# Inbox
- [ ] Do foo
- [ ] Do bar
- [ ] Do [[a very complex task]]

# Year
## Month ^MMYY
### tomorrow/month/year (weekday)
- [ ] [[Project that will take a very long time]]
- [ ] Fix [big bug] that just popped up
- [ ] Do baz

### today/month/year (weekday)
- [ ] [[Project that will take a very long time]]
- [x] Do zip
- [x] Fix small bug that just popped up
- [ ] Fix [big bug] that just popped up

### yesterday/month/year (weekday)
- [ ] [[Project that will take a very long time]]
- [ ] Do zip
- [x] Do zap
```

The daily workflow:
1. Work on the tasks in today's header in whatever order you feel like, or based on urgency. Tick them off when completed.
2. If the task turns out to be more complex than expected, create a dedicated note for it and replace the entry with a wikilink (more about this later). Sometimes I also add links to specific sub-tasks or bugs in the linked note.
3. If new tasks or bugs pop up during the day, add them at the end of the day's list.
4. If you complete all tasks for the day, select a new one from the inbox.
5. At the end of the day:
	1. *Copy* all the tasks that you *worked on but couldn't complete*, and paste them back at the *top* (instead of at the bottom, like in _Autofocus_) of the inbox.
 	2. *Move* all the tasks that you didn't touch back to the inbox.
	3. Add the next day's header, adding a new month/year header if necessary.
	4. Go through the inbox and *move* 3-4 tasks for the next day.

Very often I need more than just a bullet-point list of tasks. Some things require complex context, specific assets, screenshots, etc. Or just because they'll take multiple days and lots of research or trial and error.
This is mostly for documentation purposes, which is vital if I don't want to start working on it straightaway, or if I need to remember how I dealt with it months after it was completed.
They normally have a description, a list of links for docs and references, a list of sub-tasks, a list of bugs, and most important of all: a journal where I write down what I did and what problems I had each day. Like a personal daily stand-up ([I actually like stand-ups](http://javiersalcedopuyo.xyz/blog/2020/in_defence_of_daily_standups.html)).
This is roughly how they look:
```
// a_very_complex_task.md
# Title
## Description
Blah blah blah
![example pic](example.jpg)

## Docs & references
- [Relevant blog post](www.superinterestingblog.com/relevant_post)
- [Official docs](www.vendorproject.com/docs/foo_bar)

## Sub-tasks
- [ ] This can be linked from tasks.md ^task_example_1
- [x] So can this ^task_example_2

## Bugs
- [ ] Nasty bug found while working on this task ^bug_nasty_bug_1
- [ ] You get the idea ^bug_example

## Journal
### latest_day/month/year (weekday)
What I did that day, and why.

### latest_day-1/month/year (weekday)
What I did that day, and why.
I also found this [nasty bug](#^bug_nasty_bug_1)
...
```

And this is pretty much it!
It's simple, it doesn't require any maintenance, tasks can be added and removed without almost any friction, and it's still flexible enough to expand on tasks that require more than just a one-liner checkbox.

I'll probably continue iterating on it over time but it hasn't changed much in the last year, so I don't expect to make any revolutionary changes to it.

I hope you found it useful!
