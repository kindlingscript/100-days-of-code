# 100 Days Of Code - Log

(As I am starting at Day 0 like an array index, this will end on Day 99.)

### Day 0: January 9, 2017

**Today's Progress**: Started to configure Gulp processes for WordPress redesign of a RoR site I made last fall, to a) make it easier for people to make blog posts, and b) to get more experience with WordPress dev and design.

**Thoughts:** I struggled some with setting up the CSS Gulp processes, but with a few Google searches was able to figure it out. Google also helped with setting up browser-sync correctly. 😄

**Link to work:** [Nashville Stuttering Association WP Github repo](https://github.com/kindlingscript/wp-nashville-nsa)


### Day 1: January 10, 2017

**Today's Progress**: Worked on setting up initial PostCSS (Gulp integration + CSS organization), started to set up functions.php, and split off to make front-page.php for the homepage, saving index.php for blog page later. Added Normalize.css.

**Thoughts:** It took a bit of going back and forth to recall the code needed to integrate PostCSS successfully, but got past it pretty easily. Starting to make the CSS organization was fun. (I was going to catch up on President Obama's farewell speech first before doing this (was trying to watch + do my non-programming job at same time, no luck), but knew it wouldn't leave enough time to. So I'll watch it now, haha.)

**Link to work:** [Nashville Stuttering Association WP Github commit](https://github.com/kindlingscript/wp-nashville-nsa/commit/fecf6bf5d1cd5222fdfe93c1b92eda933ed5d24c)


### Day 2: January 11, 2017

**Today's Progress**: Started to modify the primary (top) navbar for the site, including logo to the left and button to the right. Wrestled some with adding a hero image to the front page. I think I want to make it so it can be changed out within the WP admin, so I'll look into that and see if I can get started on it tomorrow.

**Thoughts:** The navbar stuff was pretty easy, and I also thought adding the hero image would be easy as I've done it before for other sites; I was wrong lol. Got a bit peeved at the difficulties here. Hoping it comes to me after reading some more on it all soon. 👌

**Link to work:** [Nashville Stuttering Association WP Github commits](https://github.com/kindlingscript/wp-nashville-nsa/commits/master)


### Day 3: January 12, 2017

**Today's Progress**: Found a way to add in the hero image with a bit of [Google help](https://web-design-weekly.com/snippets/linking-to-an-image-folder-within-a-wordpress-theme/). But then I went back to adding in with CSS background-image for this one (at least for now), yet I have a new resource for another way. Added in the intro block, playing around with absolute positioning. For now the site looks good so far on mobile phone sizes, will make my way up to tablet and laptop/desktop responsiveness later. Oh! And I also learned some about custom post types outside of this progress.

**Thoughts:** As I'm working a non-programming job right now, I typically just get to work on this in the evenings, at least during the weekdays. I like how this is keeping me going with dev/design work so I don't "fall behind" while I work on something that doesn't involve coding during the rest of my time. I want to dive more into positioning with CSS.

**Link to work:** [Nashville Stuttering Association WP Github commits](https://github.com/kindlingscript/wp-nashville-nsa/commits/master)


### Day 4: January 13, 2017

**Today's Progress**: Helloooo, so today I added the main content sections of the front page, i.e. here's our blog, also here's where we meet with a Google Maps plugin to boot. Also added the footer for the front page(.php). Still plugging along at CSS for mobile-first, but larger screens will get CSS love soon enough!

**Thoughts:** Pretty standard day, not too easy or too challenging as I was trying to match up (to some degree) the Ruby on Rails version of the homepage to this new WordPress one. I was able to utilize the WP Google Maps plugin, and so far I like it, though the free version is missing a few things I was able to do on the RoR site, like a description when clicking on the marker instead of just the address. Not paying $40 for the pro version right now, though. ✌️

**Link to work:** [Nashville Stuttering Association WP Github commits](https://github.com/kindlingscript/wp-nashville-nsa/commits/master)


### Day 5: January 14, 2017

**Today's Progress**: A lot of tinkering with CSS for responsiveness. It's not organized and named well enough for me to feel great about it yet, that's something I'm going to be continually working on improving. Since going through most of [Brad Schiff's course on Udemy](https://www.udemy.com/git-a-web-developer-job-mastering-the-modern-workflow/), I've borrowed inspiration from him with grid-making, and kind of a BEM style. Today was going from, "This isn't working well, I don't like it," to, "All right let's start changing things up. Yeah, this is doing better."

**Thoughts:** In a sense, this first project is launching off from the course mentioned above, taking what I love from it and incorporating it into my own work ("practice makes perfect, or at least closer to perfect"). It's helping to solidify the knowledge Brad imparts in his videos. I'm also trying to break away from leaning on frameworks like Bootstrap or Materialize (or Foundation) as well. They're great for speed in getting a MVP up and running, but that's not what I'm doing here; I want to better understand how and why certain things work "under the hood," per se.

**Link to work:** [Nashville Stuttering Association WP Github commits](https://github.com/kindlingscript/wp-nashville-nsa/commits/master)


### Day 6: January 15, 2017

**Today's Progress**: Work on finishing up footer work on the front page. Responsiveness.

**Thoughts:** Most of this was pretty easy until the end, when I spent around ten minutes trying to figure out why the copyright's border-bottom wasn't visibly showing up when hovered over with the mouse. Wound up I needed to add bottom-padding to its parent class. Simple stuff like that, tripping us up every now and then to make sure we know we're still a bit dumb, overlooking things! 😉

**Link to work:** [Nashville Stuttering Association WP Github commits](https://github.com/kindlingscript/wp-nashville-nsa/commits/master)


### Day 7: January 16, 2017

**Today's Progress**: Started on coding up the blog page + registered the sidebar for said page.

**Thoughts:** Not too many about today? Um, it was a slower day probably because of other work I had to do. I'm looking forward to putting the sidebar in action on the blog page soon. Hope to start on that tomorrow. On another note, I feel that towards the end of this project, I'll be going back and giving the CSS a thorough look-through and editing to give things better names and organization.

**Link to work:** [Nashville Stuttering Association WP Github commits](https://github.com/kindlingscript/wp-nashville-nsa/commits/master)


### Day 8: January 17, 2017

**Today's Progress**: Spent time in index.php, content-blog.php, and within the CSS modules folder for the most part. I styled the main blog page for mobile screens (barring the sidebar which is still in default appearance mode).

**Thoughts:** I enjoyed playing around with the CSS until I got it to where I'm (mostly) happy for now. Used a transition hover effect on the blog entry titles, centering everything but the summary / excerpt of the entry. That will change for larger screens. Only bit of trouble I had was getting the `a` element within the `entry-summary` class div to center. I tried both `margin: 0 auto` and `text-align: center` on it, but it wouldn't work until I put the element itself within its own div.

**Link to work:** [Nashville Stuttering Association WP Github commits](https://github.com/kindlingscript/wp-nashville-nsa/commits/master)
