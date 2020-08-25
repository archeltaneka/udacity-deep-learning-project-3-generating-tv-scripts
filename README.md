# udacity-deep-learning-project-3-generating-tv-scripts
This project showcases the ability of RNN and LSTM networks to generate a new TV scripts based on a real [Seinfeld TV Scripts](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv). Here are some examples of the real scripts:

>Lines 10 to 30:
>jerry: oh, you dont recall? 

>george: (on an imaginary microphone) uh, no, not at this time. 

>jerry: well, senator, id just like to know, what you knew and when you knew it. 

>claire: mr. seinfeld. mr. costanza. 

>george: are, are you sure this is decaf? wheres the orange indicator? 

>claire: its missing, i have to do it in my head decaf left, regular right, decaf left, regular right...its very challenging work. 

>jerry: can you relax, its a cup of coffee. claire is a professional waitress. 

>claire: trust me george. no one has any interest in seeing you on caffeine. 

>george: how come youre not doing the second show tomorrow? 

>jerry: well, theres this uh, woman might be coming in. 

And, here are the results from training the model with the script:

>jerry:, i- i love that place, you know, i gotta get going. i don't want to *live*.

>jerry: what?

>elaine: what is it?

>kramer: well, i just got it. i got a little problem with him.

>jerry:(pointing out) you don't know, i was just standing there with you.

>george:(to himself) i think we should get a break..

>jerry:(to elaine) oh, you have a good friend, huh?

>elaine: yeah.

>jerry:(to the executives) yeah, yeah, well, it's a lot better, uh, just like you, uh...(he hangs up)

>george: hey.

>george:(to george) you know, i'm really sorry.

>kramer: i don't know why i was just to tell you. i can't believe this.

>jerry: i know.

>george: i don't know, i know. i'm going to have sex.

>george: what? you think you're a phony, too.

>jerry: i don't know what the hell is going on here.

>george: oh, you know, it's a little unusual idea.

>jerry: i dont know what this is about.

>george: what about the plane?

>jerry: well, you know, i was just curious.

>elaine: i was hoping that we could use a movie.

>george: i think i know what i'm gonna do about this thing.

>jerry:(to himself) yeah, right.(he gets the bottle of the table.)

>elaine:(pause) oh, oh, right, right.

>jerry: oh, thank you.

>george:(to himself) oh, my god!!!(to kramer) hey! what about that guy?

>kramer:(to the phone) yeah, i got a little unusual.

>kramer:(to jerry) you know, you know

## Prerequisites
- Numpy v.1.19
- PyTorch v.1.6.0
- CUDA 10.2 (optional for GPU training)
