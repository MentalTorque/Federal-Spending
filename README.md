# Federal-Spending
An analysis of federal spending by agency and geographic location.

Files submitted 5/6 for video and presentation.  Vidoe required compression into a zip file due to GitHub size constraints.

Worked on an initial model for the Federal Spending; it was an utter disaster.  I was thorough, but the model is simply not structured well wo get away from underfitting.  A very interesting experience.  As these assignments are part of my learning program, and I intend on using it to drive the $10M in revenue I produce annually, I find it interesting to see how these models can break, so to learn how to rectify it in the real world.  Not every model, very few in fact, will run optimally if at all on their first go around.  Part of learning data science is experimenting with the models to learn both how they optimize, and also how they fail.  Those failures will be the bedrock of future optimizations.

To rectify this model, I am hyptohesizing the following:

If I OHE the Geography feature, it'll create far more features to analyze across the model which we need considering how drastically underfit this model presently is.  This should improve the nuance of the model, allow for improved PCA, provide better clustering, and ultimately give improved accuracy to the model.

As I've been coding for 36 hours straight now, in order to have everything in to unlock the exam, I am having difficulty maintaining the rate.  I will try and get the revamped model in ASAP, but I am getting concerned that the relentless pursuit of perfection, especially in such a compressed period,  required with the submission of all of these assignments  is also going to adversely impact my performance on the incredibly rigorous exam, which I will have to commence in the next 18 hours if I am to finish by the submission deadline.  The class just learned that if you miss just half a point on the exam, it demotes you to some form of second class belt.  This setup is not very conducive to success in my opinion, considering the previous cadence disruptions of shifting dates, especially when enjoined to working 70 hours a week and raising a child.  It's a good thing I really want this.

Let's take a crack at this next model.
