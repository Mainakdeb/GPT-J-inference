# Generating Fictional Dialogues
Using the GPT-J 6B (8 bit compression) to generate dialogues from prompted context.
Prompts are bold, rest of the text is generated. 

## Zero Shot
> **Genre: Science Fiction.**

> **Scene: desert with floating ice-creams.**

> **Story plot: Mr Bean has to collect 100 ice cream flavors within a day to open a portal to the mothership.**

> **Character1: Cyberpunk Snow White princess.**

> **Character2: Mr. Bean as a Star Wars character.**

> **Script:**

> **Bean:** What's this?

> Princess: A portal to the mothership.

> Bean: A portal to the mothership..? That means I've gotta collect the 100 flavors in 24 hours..?

> Princess: Yes, you'll be going to another part of the desert.

> Bean: Hmm.. let's see. Let's see here.

> Princess: I'll give you the first one.

> Bean: Well, I accept, Princess.. *gulp* OK then.. Let's see.. Here.. First I wanna try a Milky Way. OK, let's see..

> Bean: Ok ok, that flavor is Milky Way. What's the next one? *gulp*

> Princess: A Black Cherry.

> Bean: Black

## One-Shot
In addition to the task description, the model sees a single example of the task. No gradient updates were performed. 
> **Genre: Science Fiction.**
###
> **Scene: : desert with floating ice-creams.**
###
> **Story plot: Mr Bean has to collect 100 ice cream flavors within a day to open a portal to the mothership.**
###
> **Character1: Cyberpunk Snow White princess.**
###
> **Character2: Mr. Bean as a Star Wars character.**
###
> **Script:**
###
> **Bean: Do you see the portal?**
###
> **Cyberpunk Princess:** Do you not understand my language?
###
> Bean: I do not speak English and I do not understand you.
###
> Cyberpunk Princess: So what did you expect to be the result of this mission?
###
> Bean: I expected the portal to open.
###
> Cyberwoman: How do you expect to open the portal on such a remote planet?!
###
> Bean: I know nothing of this planet, but I have a mission to complete.
###
> Cyberwoman: If you have nothing better to do than searching for ice cream on remote planets, stop bothering me.
###
> Bean: I don't think the ice cream will give me a heart attack. I think I can handle it as long as
