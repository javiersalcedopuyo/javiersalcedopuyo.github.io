## Coding Agents are Steroids

During a recent discussion with some colleagues about the use of AI for coding, I had a sudden realisation of a perfect analogy that I haven't seen out there. As the title already spoiled: *Coding Agents are Steroids*.

**Key points:**
- The core of my idea is comparing muscle mass with software *quantity*, not quality.
- The "risks" here refer to the potential side effects of using these tools on you as an *individual*. I am *not* talking about societal or environmental risks.
- This refers exclusively to agents that generate code, not chatbots. The latter can be used as learning or QA tools very effectively with virtually no "risk".

**TL;DR:**
- Both enable uninitiated people to easily get results that used to require a significant effort.
- Professionals that know what they're doing can use them to work harder and for longer, producing results previously impossible.
- Their use has serious medium to long term risks that shouldn't be taken lightly.
	- It's ok to take part in risky hobbies and careers though. As long as it's a free and informed choice.
- Due to their inherit risks, amateurs and novices should avoid them until they have reached their "natural limit". And only then consider seriously if they're worth it.

### The Bodybuilding Eras (and "Gainzflation")
Strength sports are a hobby of mine, and I know it's not a common one in our field, so I'll do a quick (simplified) recap of the main "eras" of bodybuilding:

#### The Bronze Era (19th to early 20th century)
The beginnings of the discipline. The basics of training and nutrition were still being discovered, and it was mostly an age of experimentation, but 100% natural.
Some of the exercises and machines used back then now look bizarre, dangerous, or even counterproductive.
The main goals were size and strength.
My favourite example is probably *Medicine Nobel laureate* Santiago Ramón y Cajal:  
![Ramon Y Cajal](img/ramon_y_cajal.png) 
Nowadays almost anyone can reach this level with a basic (modern) workout plan and a healthy diet.

#### The Silver Era (1940s and 1950s)
The discipline was mostly developed by now. The workout plans, gym equipment, and diet  was very similar to what you would find nowadays. Performance Enhancing Drugs (PEDs) didn't really exist yet.
The ideal was the Greek statue look.
My personal favourite was Steve Reeves:  
![Steve Reeves](img/steve_reeves.png)  
Today these physiques are only competitive in amateur competitions, but they achievable by the average person in a couple years with a well designed workout plan and a strict diet.

#### The Golden Era (60s to 90s)
PEDs appear and completely change the game, but they were still very new, limited, and poorly understood. The cost of this experimentation was high, and many died young.
Workout plans, exercises and nutrition improved, but they were still fundamentally the same as in the Silver Era.
The ideal was also the same as in the Silver Era, just bigger.
An obvious example is young Arnold:  
![Arnold Schwarzenegger](img/Arnold.jpg)  
Today these physiques are relatively common among amateurs (you can see at least one person like this in every commercial gym), and are even expected of action movies' male protagonists. But it still requires expensive (and illegal) drugs, a well designed workout plan, and a very strict diet.

#### Mass Monster Era (90s to 2010s/Today?)
PEDs become more abundant, potent and better understood.
People started using complex combinations of PEDs (sometimes guided by medical teams) and pushing their bodies to the limits not of muscle but of bones, tendons and internal organs.
It's important to note they didn't use them as shortcut. The main use of PEDs is that they make you tolerate higher workloads, and recover faster. Some PEDs just allow you to digest and assimilate larger meals.
The goal was size at all costs. See legendary Ronnie Coleman:  
![Ronnie Coleman](img/ronnie_coleman.webp)  
This is still the peak of "open" bodybuilding. It remains rare, and only people who dedicate their whole lives to the sport reach this level.
With modern PED "stacks", you could reach a Bronze or even Silver era physique without even having to workout (and you'd pay a heavy price health-wise for it).

### The Programming Eras
There's no exact match, but for the sake of my argument I'll try to *roughly* mirror them in our field's history. Not necessarily by timeline, but by technology.
A big and crucial difference is that, while in *professional* bodybuilding each era displaced the previous one, in programming they all coexist.

#### Experimentation (Bronze) Era: COBOL to C
As with the bodybuilding equivalent, the discipline itself was still forming.
Multiple programming paradigms, language families, and conventions were being developed and tested.
Most programmers were mathematicians or electrical engineers with a deep knowledge of both the hardware and the software stack that was necessary to produce good results.

#### Abstraction (Silver) Era: C++ to Java and OOP
C became the gold standard, conventions like 0-indexing or classes were stablished, and new technologies like the JVM or garbage collection were proposed as "the perfect solution for all our problems".
People started to work on abstractions that arguably made life easier, and required less and less knowledge of the lower layers.
Developer "ergonomics" were getting more weight, but performance was still an important consideration, and compiled languages still dominated.

#### Convenience (Golden) Era: JavaScript to AI Autocomplete
The compounding improvements in hardware, and the popularity of the Internet gave rise to interpreted, dynamically typed languages like Python or JavaScript. Performance and correctness were sacrificed in the altar of "developer speed".
Electron brought JS to even apps that in the past were precompiled, and that's how we got Microsoft using React in the Windows 11 Start menu.
Bloated IDEs provided a lot of tools to automate work, and it culminated with AI autocomplete (a glorified snippet engine in my opinion).

Like in its bodybuilding counterpart, the processes were still similar to the previous Silver era (manual design, C-like syntax, etc) but we reached new levels of software production, previously impossible. And also at a high price in some cases.

Programming became so accessible that you could get a good job with just a couple weeks of Bootcamp.

> NOTE: This era might mirror the "golden" era of bodybuilding, but personally I consider it the furthest from "golden". The quality of the average piece of software plummeted. This was the era of "human slop".

#### Agentic (Monster) Era
Software production speed at all costs.
Anyone with a computer can create a *functional* application. But domain experts can now use agents to amplify and speed up their work by several orders of magnitude.

Most people talking about agent swarms and stuff like that will probably just end up spending a lot of money and damaging their careers in the process, but I can see a small group of *really good* (better than me at least) programmers using them to produce things by themselves that in the past took entire teams.
We'll probably have to wait for several years before really knowing which risks came true, and what was the real cost of all of this.

The Dunning-Krueger effect will hit hard here (in which camp do *you* fall?).

### The Risks of Using Agents
#### Skill Atrophy and Tool Dependency
It is very likely that you will lose the patience, or even the capacity to navigate unfamiliar code bases and think deeply about a problem.
Eventually, you will be unable to do your job without access to these tools, which is something scary if you ever lose access to them.

But the same way that PED users follow other treatments to compensate for the side effects (which include *physical* atrophy), you can do the same: Make sure you dedicate some time regularly to work unassisted. Extra points if you do it with minimal tools (no IDE for example). The harder you make it, the more you'll resist the atrophy.

#### Economic Dependency
Your work capacity now depends on a subscription.
Personally, I find that *very* uncomfortable, but it's not unheard of.
Following with the bodybuilding examples, PEDs are expensive, they need to be taken regularly (sometimes for the rest of your life), and you'll need regular blood tests and medical checkups.

You can run a local model, but they're not nearly as good. In a similar way, there are PEDs that are safer than others, but they also bring much less benefits.

If your employer pays for it, it not *that* bad. But what would happen if you lose that job? Or if they decide it's not worth continuing to pay for it?

There's also a very real risk that this is just not economically viable. At the moment token prices are heavily subsidised to encourage people to get into it (like the fabled shady guy in the locker room offering you a "free cycle"). As such, we don't have a real price mechanism to tell us how useful this really is. There's a very real (and even likely) possibility that, for most people, it's actually cheaper and more efficient to not use them at all.

#### Quality Decrease
You are ultimately responsible for the quality what you produce, be it "organically" or through an agent.
If you increase your use to the point where you can't possibly check its output, your work's quality will almost certainly deteriorate over time.
A decreasing quality in your output will in turn damage your reputation and job stability.

Even in the best case scenario, where you can just use more agents to check or fix the output of other agents (and assuming they'll do a perfect job at it), the cost of maintenance will still continue to increase; just in terms of tokens, money, energy, or all of the above. That will then become a question of economics but my bet is that, on the medium to long term, it'll be more expensive than you taking the time to verify.

#### AI Psycosis
You could just go crazy.
"[Roid rage](https://en.wikipedia.org/wiki/Roid_rage)" for nerds.

### The Way I See It
My position is basically the same as with PED use. Which has always been this:
> If you are an adult, aware of the risks and health consequences, you do you.

My point being: it's ok to take *informed and voluntary* risks in pursue of excellence in your craft, or if your chosen profession requires it. It's, obviously, also ok *not* to take them.
No one bats an eye when a firefighter, a miner, or extreme athlete put themselves in *real physical* danger for their work. Our risks for using agents are astronomically smaller.

However, *if coding is your hobby, or you're early in your career*, I do not think you should be regularly using agents, the same way I think an amateur gym-goer shouldn't be taking PEDs.
Before starting with PEDs, an athlete must reach their "natural limit". If you haven't got there yet, you're paying a high price unnecessarily. You could've gotten the same results without damaging your health. And you will seen as a wimp who's not willing to put in the work.  

From what I see online, the people that are really excited about this basically fall into 2 categories:
- Veterans with decades of experience seeing the potential of streamlining and automating the tedious and bureaucratic parts of the job, so they can focus on thinking about the truly difficult parts (They have reached the "natural limit").
- Noobies that think this is a magic genie that will do all the work for them (They just want quick results).

So, if you are a junior programmer and your work requires you use agents, my advice is to keep this in mind and work on AI-free projects at home as much as possible.