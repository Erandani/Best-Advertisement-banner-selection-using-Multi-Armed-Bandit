# Best-Advertisement-banner-selection-using-Multi-Armed-Bandit

We are running a website and have 5 different banners for the same AD, we need to know which banner attracts the user most.
We model this problem statement as a brandit problem where 5 banners are 5 arms of the brandit and awards 1 point if user clicks the AD and awards 0 if user does not.
In normal A/B testing, we will perform complete exploration of these 5 banners before decide which banner is best. But it will cost more time and resources. Instead here we will use optimal balance between exploitation and exploration.

