# The Era of Experience: David Silver on AI's Next Frontier Beyond Human Data

(The Source)[https://www.youtube.com/watch?v=zzXyPGEtseI]

## Introduction: A Bold Vision for AI's Future

David Silver, the architect behind AlphaGo's historic victory over human Go champions, has a provocative message for the AI community: large language models are not the only path forward, and we need our AIs to figure things out for themselves to discover new things that humans don't know. As an original DeepMinder and one of the key figures behind the first program to master the world's most complex board game, Silver brings unique authority to his bold proposal for AI's next phase—what he calls "the era of experience."

In a recent conversation on the Google DeepMind podcast with Professor Hannah Fry, Silver laid out his vision for moving beyond the current paradigm of AI systems that learn primarily from human data. His argument is both simple and profound: if we want AI to go beyond human capabilities, we need to stop limiting it to human knowledge.

## The Bitter Lesson of AI

Silver describes what has become known as the "bitter lesson" of AI—a hard truth that many in the field struggle to accept. "We really want to believe that all of the knowledge that we've accumulated as humans is really important," he explains. This desire leads developers to feed human knowledge into their systems and build it directly into their algorithms. 

However, Silver's experience with AlphaGo revealed something counterintuitive. The original version of AlphaGo, which famously beat Lee Sedol in 2016, was initially trained on a database of human professional Go moves. This gave it a starting point before it learned further through self-play. But when Silver's team created AlphaZero a year later, they made a radical decision: throw out all human data entirely.

"What we discovered was that the human data wasn't necessary," Silver reveals. Not only could the system recover the same level of performance without human examples, "it actually worked better and was able to learn even faster than the original AlphaGo to achieve a much higher level of performance."

This finding challenges our fundamental assumptions about learning and expertise. When we design algorithms fitted to human data, Silver argues, we make them "less good at actually learning for itself." By removing human constraints, the system can dedicate all its resources to discovering optimal strategies through experience.

## From Human Data to Self-Generated Experience

The current AI landscape, according to Silver, exists in what he calls "the era of human data." Large language models and similar systems operate on a common principle: extract every piece of knowledge humans have created and feed it into the machine. While this approach has produced incredibly powerful results, Silver sees a fundamental limitation.

"Human data is grounded in human experience," he notes. LLMs inherit information that humans figured out through their own experiments—like discovering that walking on water doesn't work but boats do float. However, this inherited knowledge comes with a ceiling. "There is a ceiling to everything that humans have done," Silver emphasizes. "We need to break through these ceilings."

The alternative Silver proposes is systems that generate their own experience through interaction with the world. Rather than learning from human examples, these systems would try things out, build up experience, and discover patterns humans never found. This approach enables what Silver calls "sustainable fuel" for AI progress—as systems grow stronger, they encounter problems appropriate to their level, generating experience that enables them to solve the next challenge, continuing indefinitely without limit.

## The Magic of AlphaZero

To understand Silver's vision, it helps to examine how AlphaZero actually works. The system is, in Silver's words, "surprisingly simple." It begins with a policy (a way to pick moves) and a value function (a way to evaluate positions). Through self-play, it searches for the best moves according to its current understanding, then trains itself to make more moves like the successful ones while updating its evaluation based on actual game outcomes.

"You just iterate that millions of times," Silver explains, "and out pops a superhuman game player. It's like magic basically."

The sense of magic was particularly strong when the team tested AlphaZero on Shogi (Japanese chess), a game none of them knew how to play beyond the basic rules. Silver recalls: "We just plugged it in and it was literally the first ever time we ran AlphaZero on Shogi. We had no idea whether it was good or not. We couldn't evaluate it." 

They sent the games to Demis Hassabis, who knew the game reasonably well. His assessment: "This looks quite good. I'm sending it to the world champion." The world champion's response: "I think this is superhuman."

"It literally felt like magic," Silver reflects, "because we just pressed go on this system and had no idea of the process and how it got there, but somehow out popped a superhuman Shogi player."

## Move 37 and the Promise of Alien Intelligence

One of the most celebrated moments in AI history came during AlphaGo's second game against Lee Sedol: move 37. This move, played on the fifth line of the Go board rather than the traditional third or fourth lines, defied centuries of human Go wisdom. Silver's team estimated only a one in 10,000 probability that a human would ever consider such a move.

"Humans were shocked by this move," Silver recalls. "Here's something creative that happened. Something that a machine came up with that was different from the way humans traditionally thought about the game that actually was a big piece of progress and took us beyond the confines of human knowledge."

This moment represents something crucial for Silver's vision. Move 37 wasn't just a good move—it was an alien move, a strategy that emerged from pure self-play without human conceptual constraints. For Silver, it's not just a single discovery but "one of an infinite series of discoveries where the system can just keep on learning and learning and learning."

When asked whether large language models have produced their own "move 37" moments, Silver is skeptical. "Because we've been in the era of human data, we focused a huge amount on reproducing human capabilities and we've focused much less on going beyond them. When you're anchored in human data, you're only ever going to have human-like responses."

## Mathematics: The Next Frontier

Silver's team has recently applied these principles to mathematics through AlphaProof, a system that learns through experience to prove mathematical theorems. The system works with Lean, a programming language that can express all of mathematics in formally verifiable form.

Starting with about a million human-generated mathematical problems (but crucially, not their proofs), the system generates 100 million formal problems. Initially, it can barely solve any of them—"99.999% of the theorems it just can't do," Silver notes. But through reinforcement learning, using successful proofs as rewards, it gradually improves.

The results have been remarkable. AlphaProof achieved silver medal-level performance at the International Mathematics Olympiad (IMO), a competition for the world's most talented young mathematicians. This places it in the top 10% of contestants globally. On one particularly challenging problem that less than 1% of human contestants solved, AlphaProof found a perfect proof.

"We really want to go beyond human mathematicians," Silver states, "and that's where we'd like to go next." While acknowledging they're "a long way" from solving grand challenges like the Riemann hypothesis or other Clay Mathematics Institute millennium problems, Silver believes it's coming: "I personally would be amazed if AI mathematicians don't transform the whole of mathematics."

## The Challenge of Messy, Real-World Rewards

The most significant challenge to Silver's vision—one he readily acknowledges—is that most real-world problems lack the clear win/loss signals of games or the verifiable correctness of mathematical proofs. This absence of clear metrics is "probably the reason why reinforcement learning methods or these experience-based methods have not yet broken into the mainstream of absolutely everything that we do in every AI system."

Silver proposes that the real world actually contains "innumerable signals"—likes, dislikes, profits, losses, pleasure, pain, yields, material properties. The key is building systems that can adaptively determine which signals matter for which situations. A human might specify a high-level goal like "improve my health," which the system would translate into measurable objectives like resting heart rate or anxiety levels, adapting the mix based on feedback.

This approach could even improve safety, Silver suggests. A system optimizing for human well-being that receives distress signals when creating too many paperclips would adapt its objectives, unlike a system rigidly pursuing a fixed metric. However, he emphasizes the need for extreme care: "We absolutely have to take this very seriously and be extraordinarily careful about taking these steps."

## Beyond Synthetic Data: The Fossil Fuel Analogy

When addressing the current interest in synthetic data to overcome the limitations of human training data, Silver draws an illuminating analogy. Human data, he suggests, is like fossil fuels—a finite resource we discovered and are now "burning" in our LLMs for immediate performance gains. But just as the world needs sustainable energy sources, AI needs what reinforcement learning provides: sustainable fuel.

"This experience that it can keep generating and using and learning from and generating more and learning from it—that's really the process that's going to drive progress in AI," Silver argues. The crucial difference from synthetic data generated by existing models is that self-learning systems generate experience exactly appropriate to their current level, enabling unlimited progression.

## A Warning About Grounding and Human Feedback

Silver offers a provocative critique of how current systems use human feedback. In reinforcement learning from human feedback (RLHF), humans judge the system's outputs before seeing real-world consequences—like rating a cake recipe before anyone bakes or tastes it. This, Silver argues, creates "ungrounded" learning.

"A grounded outcome would be someone actually eats the cake and the cake is either delicious or disgusting," he explains. This grounded feedback allows systems to discover genuinely new solutions—recipes that expert chefs might assume would be terrible but turn out delicious.

Using AlphaGo as an example, Silver asks us to imagine if after every move, the best human Go player judged whether it was good or bad. "It would not end up discovering move 37 because it would just end up playing like the human thinks is a good game of Go and it would never discover the new ways to play Go that that human didn't know about."

## The Risk and Necessity of Untethering from Human Data

Silver doesn't minimize the risks of his proposal. Creating AI systems that learn independently from human data and potentially develop over extended periods—having what he calls "a life"—raises serious concerns about alignment and control. Current AI lacks this continuous stream of experience that allows for long-term adaptation and learning.

Yet Silver sees this transition as inevitable and necessary. His motivation for writing his position paper was concern that "people aren't recognizing that this transition is going to come and that it will have consequences and it will require careful thought." The field's focus on human data approaches means "not enough people are taking seriously these kinds of questions."

When asked if he still believes his earlier position that "reward is enough" for achieving AGI, Silver refines his view. Human data gives us a head start—like fossil fuels jumpstarting industrialization—but reinforcement learning provides the sustainable path forward. "I don't want to in any way denigrate what's been done with human data," he clarifies. "AIs that we've got now are amazing, mind-blowing things. I love them and enjoy working with them and do research on them myself. But it's just the beginning."

## AI Designing Its Own Learning

In a fascinating development, Silver's team has even created systems that design their own reinforcement learning algorithms. Through trial and error—using reinforcement learning itself—these systems figured out what algorithms work best for reinforcement learning, going "one level meta." The result: AI-designed algorithms that outperformed all human-designed reinforcement learning algorithms developed over many years.

"This is the same story over and over again," Silver observes. "The more of a human you put into something, the worse it performs. Take the human out, does better."

## Conversation with Fan Hui: The Human Side of AI's Triumph

In a special segment, Silver reunited with Fan Hui, the European Go champion who became the first professional player to face AlphaGo in October 2015. Their conversation reveals the profound psychological and philosophical impact of AI's breakthrough.

Fan Hui's experience was transformative. "I still remember when I play with AlphaGo first game I lost I feel something strange," he recalls. After the second loss: "I feel fear because I feel maybe I will never win with this program." By the fifth game: "I feel my Go world is broken."

Yet this breaking led to rebuilding. "Maybe this is also the good moment—my new Go is open," Fan Hui reflects. The experience fundamentally changed his mindset: "Even today for me I never ask a question like I can't or I can. My question always like I want or I don't want. This is AI or AlphaGo teaching me about that."

Fan Hui noted that AlphaGo felt fundamentally different from other computer programs he'd played: "When I play with another program I feel like this is a program because they don't play like a human. But with AlphaGo I feel something very strange. Sometimes I feel like it's really, really like human."

The Go community's acceptance came gradually. After Fan Hui's loss, "nobody really believe this is true because I'm only European champion, not world champion." But AlphaGo's victory over Lee Sedol, particularly move 37 in the second game, changed everything. "Such beautiful move, really really beautiful, so creative," Fan Hui emphasizes. "For the human we will never play this move. After that move everything change in the Go world because for us everything is possible."

Today, the transformation is complete: "Even the Go student use AI to learn. I think this is really really good for our Go community. I think it's not just for Go community, it's also for the world."

Silver, reflecting on the uncertainty before that first match, admits: "We really weren't confident. We knew that we'd gone beyond all the programs that had been written before, but there's such a huge gap beyond that towards the level of professional players like Fan Hui. We just genuinely didn't know." The team wouldn't have been surprised by losing all five games, making the 5-0 victory "a very pleasant surprise."

## Conclusion: The Dawn of a New Era

Silver's vision of the "era of experience" represents a fundamental shift in how we think about AI development. Rather than viewing human knowledge as the pinnacle to be replicated, he sees it as merely a starting point—useful fossil fuel that got us going but ultimately limiting.

The path forward, in Silver's view, requires courage to let go of human constraints and allow AI systems to discover genuinely alien solutions through their own experience. This doesn't mean abandoning human values or goals, but rather creating systems that can pursue those goals through methods we never imagined.

As Professor Hannah Fry observed in closing the main interview: "If we really want superhuman intelligence, maybe it is now time to step away from the human." The examples of AlphaGo's move 37 and AlphaProof's mathematical discoveries suggest this stepping away might reveal not just better solutions, but entirely new ways of understanding our world.

The risks are real, the challenges substantial, but for Silver, the potential is unlimited. In a world where AI systems learn from their own experience, continuously generating new challenges and solutions, the ceiling isn't human knowledge—it's whatever the universe itself allows. And that, Silver believes, is where AI needs to go next.
