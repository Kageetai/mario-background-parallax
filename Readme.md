mario-background-parallax
=========================

Super Mario Scrolling Background with only CSS

I wanted to try to build a super mario level background complete with parallax scrolling effect and little running mario. The hard part was my eager to do it without JavaScript. So only CSS! The sprites are from here: http://www.spriters-resource.com/snes/smarioworld/
I have not done any performance testing, could be quite heacy because much shifting of backgrounds.
Just one little JS-file is used [to get rid of the annyoing vendor-prefixes](http://leaverou.github.io/prefixfree/).

I also wanted to make the backgrounds scalable to the window size, but that was harder than expected because relative sizes are bad for looping animations. Maybe someone has an idea? :)

Codepen.io: http://codepen.io/Kageetai/pen/sJtjy