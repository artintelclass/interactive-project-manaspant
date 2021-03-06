# Interactive-Project
This project is due Monday, February 19th.

## Prompt
Come up with some project call that you have been awarded. Perhaps you got awarded the job of coming up with a system that allows people to use gestures in their home to activate/deactivate various appliances/lights/etc. Or perhaps you got awarded the job to create a system that tracks and understands museum vistor movements in a space and triggers various sounds, visuals, and/or something else in an interactive installation. Or perhaps you were awarded a project tasked with building an interface for a new musical instrument, or maybe a game project, or.... (fill in the blank). This project could take many forms, but needs to include realtime machine learning trained with one or more sensors, and some sort of output. Be as detailed as possible about the project call, what is the setting, what the input should be, what the output should be, etc. Don't start thinking about the tech first, think about the thing you want to create first. After that, then think about what tools are needed for building the project.

## Expectations
This project is one of the 4 major projects due during the semester and should be much more developed and polished than the weekly exercises. Having said that, it doesn't have to be an enterprise solution, it can certainly be at a proof of concept stage. As mentioned above, you have to use some sort of machine learning as a processing step between your input and your ouput. However, that doesn't have to be limited to Wekinator strictly. You are free to use other platforms if you prefer. If you have questions about what I will consider as "Machine Learning", please ask. 

The documentation for this project should be more much detailed as well. Take videos/pictures every step of development, so you can tell a story later. You're documentation should include whatever other informative information you can provide as well, like sketches, text, diagrams, etc. We will do user testing in class. Your documentation should address your user testing feedback. You don't have to accept all user testing feedback, but you should explain why you did not. Your original proposal should be included in your documentation as well.

Push all code and assets needed to run your project to your repo. You should also include detailed instructions on how to set up and operate your project.

## Deadlines
* Idea Proposal - Due Feb. 5th
* Working Prototype - Due Feb. 14th
* ***Finished Version - Due Feb. 19th*** 

## Grading Rubric
* 20% Idea Proposal - Due Feb. 5th
* 20% Working Prototype - Due Feb. 14th
* 20% Creativity
* 20% Clear Interaction - it's very clear to a user what they are doing, and how they're doing it
* 20% Consistent - the system works consistently

## Documentation

As the head of Electronic Arts, I was given the task of reviving an old classic game using new technology. Not only was I supposed to come up with a game, but another oobjective was to make sure that my creation has some meaning. 

My project is using the leap motion to control the snake in the classic snake game. Using hand gestures, I will be controlling the directions of the snake. 

Initially my plan was to use the kinect to make something similar to the tilt brush. However, in one of the classes I saw someone else use the Leap Motion as an input. I thought that this was a good opportunity for me to explore a technology that I had not in the past. This would give me a good opportunity to not only learn a bit about the Leap Motion but would also help me explore a lot of hand gestures that come with it and use them in my project.

The first step in my project was to figure out whether or not the Leap Motion was reliable enough to use as input. So, for the user testing day, I connected my Leap Motion input to a sound output and used continuous outputs. 
These were the results of the different user tests. 
[1](https://www.youtube.com/watch?v=GuW2UtWIzAU), [2](https://www.youtube.com/watch?v=eKlrWJCkOg4), [3](https://www.youtube.com/watch?v=N2nOqKBLDso)

My input was working fine in all these cases. So, I thought that now that I know that my input is reliable I can get a bit more adventurous with my output. I decided to do something with sound. I decided to make an air DJ output where gestures would lead to different sound effects. On further research on the internet, I found that this had already been done before and I lost interest in the idea. 

I started thinking of some other idea and decided to do something with a game. I had recently played snake on my grandmothers old phone when I had gone back home during the winter break. This gave me a great idea to use the leap motion to control the direction of the snake. 
It seemed like a good juxtaposition as well. The snake comes across as a very old and primitive game. Leap Motion on the other hand is a very modern and advanced technology. Connecting these two seemed like a cool and also a meaningful project. It shows how easily old projects can be 'remixed' and brought back to life. It makes these old projects relevant for the new generation who might not really identify with the old game but with the new technology they might also get attracted to it. 

A challenge for me was to connect the snake game to wekinator. Since I have not done Java before, it took me some time to figure out where to edit the code to connect it to Wekinator. Then, I added some outputs in the code for the 4 different directions. 
Another huge challenge was to get the gestures to work. I still havent been able to find the perfect solution. I think it is a shortcoming of Leap Motion. Change in hand size affects the recognition of the gesture. This might be a problem if someone with a significantly different hand size comes to play the game. 

One of the first gestures I used were based on very different hand positions. Some of the examples can be found in these videos( [1](https://youtu.be/OlMT8GM6H2c), [2](https://youtu.be/ffHN9aNQ6fU)). After user testing I was told that these gestures were very inconvenient. The hand was being made to make awkward positions that were very counterintuitive to the directions of the game. This was the old input [gesture](https://youtu.be/zVX7ZaPZNoM).

Because of this I also tried other input like the webcam. I thought of using the facetracker to track the movement of the face and change the snakes direction based on that. 

I changed that to some face gestures using my web cam. On some user testing I realized that these were very inconvenient. So on Yuxin's recommendation I changed my gestures to finger based now. Something like [this](https://youtu.be/R84GqbQZ0y0) and [this](https://youtu.be/RMiDuGbTjXk). 

