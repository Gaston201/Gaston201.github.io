---
layout: post
title:  "Examination 1"
date:   2016-11-14 12-28-02 +1000
comments: true
---

Pre-compiling CSS is really amazing since you get to work with variables with makes everything both faster and easier,
where as in regular CSS you would have to constantly change the same thing in multiple places if you would for example
 want to have the same font color in different parts.

For this project I've mostly used variables, some partials, some nesting, a few extend and one or two mixins.

Pro: Variables and other techniques, less copy and paste(DRY) when it comes to html files, less manual work like not
having to add every new post to the html files.

Con: Takes some time to learn, more tools and setup, harder to debugg.

When it comes to pros vs cons the pros outweigh the cons in my opinion.
<br>
<br>
<br>
When it comes to static site generators the only one I have experience with it's Jekyll, and my biggest point about Jekyll
is that it's somewhat annoying to learn. Information and guides are limited to say the least, and you generally
end up looking at other peoples work and trying to guess your way from there. But besides that I think static site
generators are a step forward and I also the fact that it's really secure is pretty neat.

Static sites are quick and cheap develop while'st are unable to have more advanced functions which makes them most
suitable for simple sites like a run of the mill blog or maybe an introduction site for a small company.
<br>
<br>
<br>
Robots.txt is a text file that gives instructions to web robots, if you for example don't want search
engines to show a link to a certain page you could disallow it but it's important to remember that these instructions
 aren't necessary mandatory.
The robot.txt file for this site tells the robots to not look at any sites because I like my privacy.
<br>
<br>
<br>
The humans.txt file however is some text for those interested. You generally have the names of those developing the site
and other info like that, LocalHost404's humans.txt is a short one with the developers name, a "thanks for visiting"
and a date when the site was last updated.
<br>
<br>
<br>
Implementing comments was fairly easy but also somewhat annoying. Like the instructions said, I added a variable called
comments to the YAML Front Matter and made it's value equal to true. And in between the {% if page.comments %} and
{% endif %} tags in the post layout, added the "Universal Embed Code", finally made an account for disqus. But that
didn't work, I only got a message that disqus couldn't load and was linked to the troubleshooting guide. After trying a
few things I finally got it to work by removing the first function of the "Universal Embed Code". And then I had a
comments section.
<br>
<br>
<br>
Open Graph is used to help you share your website on social media. Open Graph basically just makes your website come up
as you'd think when you usually write a link in your facebook feed. The good thing here though is that you can decide
just what shows up when anyone shares the link to your website. It's most prominent use is to give you the options to
you need to promote your website in the best way possible by making your website into a rich object in a social graph.


