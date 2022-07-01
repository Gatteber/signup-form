# signup-form
A signup form to practice HTML, CSS, and SASS.



Photo by <a href="https://unsplash.com/@fedechanw?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Federica Galli</a> on <a href="https://unsplash.com/s/photos/anime?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>


### Reflection ###
Overall, this project went alright. I definitely need more practice with form validation. The most prominent thing I noticed is that styling forms doesn't seem to work the way I think it does. I think I want to experiment more with them and may end up building another test form before moving on. I've used a little scss before, and I had a nasty surprise when I accidently started editing the css file and I ended up having to re-do some of my work from the previous session.

Some of the issues I need to fix for future projects:
1.) I can't seem to get classes to actually apply to the form, it seems the that :invalid, :valid, etc pseudo-classes supercede any sort of styling applied to them, but I didn't want to redo everything on the project just for that. In the future, it seems like validating using JS, especially for something like passwords, is more ideal.

2.) I'm still not entirely comfortable with images and how they affect the document flow when using fixed/absolute positioning. I think overall, I'm caught between wanting to try more with responsive design but it ends up biting me with static images outside the document flow (in general this really seems to be a bad idea unless the image is locked down somewhere).

3.)I didn't attempt to validate with JS, because I couldn't get the error class working. I think I understand how I would do it (add an onclick listener to the button, have it select the two password fields and if they're equal, do nothing, otherwise add a form. Something like:

const getSubmit = document.querySelector(.'submit-btn)
const checkPw = document.querySelector('.password')
const checkConfirm = document.querySelector('.password-confirm')
getSubmit.onClick () => {
    if (checkPW === checkConfirm) {}
    else {checkPw.classlist.add("error")
};

I have no idea if it actually works like that, but that's what I'd guess you would do.

4.) I need to practice more with not using my mouse, and try to use more shortcuts. I use some of them, but I still need to practice more.

5.) I feel like I'm messy with organizing css, I want to get better and find some kind of self-made system to work within.

As always, below are my notes:

breakpoint- 390 x 600// wrong

Don't update css only!!!

Design ideas:

Left side - Sidebar
box (fixed pos)
image (absolute)
div with text/logo
footer on image with link to site.


right side - form
empty space on top
cta with quote
form
create account button
log in ref