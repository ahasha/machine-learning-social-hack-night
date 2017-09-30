# machine-learning-social-hack-night

This is a GitHub collaboration site for members of Machine Learning Social Hack Nights, a [meetup group](https://www.meetup.com/Machine-Learning-Social-Hack-Nights/) group for techies and tinkerers who want to deepen their understanding of Machine Learning and Data Science while connecting with like-minded neighbors. 

We will discuss journal articles starting with a focus on Deep Learning but evolving with the interests of the group. We'll also have informal hacking sessions where you can show and tell your side project or just get help with something (eek, how do I install tensorflow!?)

You should feel enthusiastic about reading technical journal articles, writing a few lines of code, pushing to GitHub, and being friendly and encouraging with other nerds. Otherwise, all experience levels are welcome! Bring your curiosity and a laptop if you want to hack on a side project. 

## Next meetup

Our [next meetup](https://www.meetup.com/Machine-Learning-Social-Hack-Nights/events/243635694/) will be on Thursday 10/5 at the offices of [Mobeewave](http://mobeewave.com/en/home-2/) (Thanks Raphaël!)

* 6-6:30: Arrive and introductions
* 6:30-8:30: Discussion and hacking time
* 8:30-9: Plan topics for next time, cleanup and depart

We will be following up on the topic of our first meetup, character-level deep learning networks for text understanding.

Last time, we looked at two papers: [Character-level Convolutional Networks for Text Classification](https://arxiv.org/abs/1509.01626), and a precursor paper with overlapping content: [Text Understanding from Scratch](https://arxiv.org/abs/1502.01710).

We found two implementations of the networks described in the paper on GitHub, which we will use as a starting point for some tinkering.  

* [https://github.com/zhangxiangxiao/Crepe](https://github.com/zhangxiangxiao/Crepe)
* [https://github.com/NVIDIA/DIGITS/tree/master/examples/text-classification](https://github.com/NVIDIA/DIGITS/tree/master/examples/text-classification)

A key question we had was how exactly the input data is structured to feed into the neural network.

As always, feel free to propose your own topics and see if you can get a few others to look into it with you.




## Venue

The venue for our next meetup has been generously provided by [Mobeewave](http://mobeewave.com/en/home-2/)

80 Queen street Suite 502, Montréal, QC
  

## Example Agenda

- Introductions and ice breaker (20 minutes)
- Announcements from members
- Breakouts (1 hour, groups of five or more):
	- Journal club discussions 
		- One participant gives a 5-10 minute overview of the paper, identifying 1-2 key takeaways, and 1-2 things they didn't understand. 
		- General discussion
		- Nominations for next session papers, to be voted on in GitHub offline. 
	- Show and tell:
		- Share a project demo, or just an idea
		- Share something you're blocked on and get debugging help from the group 
		- Keep feedback encouraging and helpful. Thought provoking questions are welcome, but "That's not a good idea" is not. 
- Hack time (30 minutes)
- Share ideas for next time (10 minutes)
- Cleanup, schmooze, depart

## RSVP policy

Our available venues currently have limited space, and the goal of the meetup is to be small enough to encourage conversation and connection.  Therefore, when space is limited, priority will be given to members who have engaged with the agenda creation process by suggesting or voting on readings for Journal Club, or submit hacking ideas or show-and-tell topics.


## Paper and Book suggestions for the Journal Club

For the journal club portion of the evening, we will select a paper or topic as a group and read them in advance.  If there's something you want to suggest, [submit a pull request](https://help.github.com/articles/creating-a-pull-request/) to add it below! 

Members are encouraged to post discussion questions on the [issues page](/ahasha/machine-learning-social-hack-night/issues), and those who do will be given priority to attend if space is limited.

### Introductory

For folks who want to learn more about the foundations, or help others learn...

* What does the "back propagation" algorithm do, and how does it work?
   * [Section 6.5 of "Deep Learning" by Goodfellow](http://www.deeplearningbook.org/contents/mlp.html)
   * [Good old Wikipedia](https://en.wikipedia.org/wiki/Backpropagation)
   * Study this simple [python implementation](https://github.com/mattm/simple-neural-network/blob/master/neural-network.py)

### ... Not Introductory

For folks who want to move past media hype and explore the state of the art...

* [Explaining and Harnessing Adversarial Examples (Goodfellow et al 2014)](https://arxiv.org/abs/1412.6572)
     * There's a lot of discussion of how deep learning algorithms are vulnerable to adversarial attacks.  This paper seems like a good entry point into that literature.
* [NO Need to Worry about Adversarial Examples in Object Detection in Autonomous Vehicles (Lu et al 2017)](https://arxiv.org/abs/1707.03501)
   * I, for one, would prefer not to worry about hacked autonomous vehicles.  Maybe this paper will put my mind at ease?
* [Deep Photo Style Transfer (Luan et al 2017)](https://arxiv.org/abs/1703.07511)
   * This one is just fun and cool.  Check out the example images [here](https://github.com/jcjohnson/neural-style)
* [Text Understanding from Scratch (Xiang and LeCun 2016)](https://arxiv.org/abs/1502.01710)
   * Cool example of how deep learning algorithms are being applied to natural language models.

## Group Hack / Show-and-tell ideas

For those who like to tinker and/or share what they've made -- post your ideas below by submitting a PR!

### Hacking

* Use this [neural style implementation](https://github.com/jcjohnson/neural-style) to create our own cool pictures.
* Work through one of these [Tensorflow tutorials](https://www.tensorflow.org/tutorials/) together
* Deploy and tinker with a [deep learning server in AWS](https://aws.amazon.com/blogs/ai/the-aws-deep-learning-ami-now-with-ubuntu/)


### Show and tell

* Be the first to sign up! Submit a PR!
