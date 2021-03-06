# #100DaysOfCode Log - Round 1 - Lev Lazinskiy

The log of my #100DaysOfCode challenge. Started on May 5, 2020.

## Log

### R1D1 5/5/2020
Cracked open [freeCodeCamp](https://www.freecodecamp.org/) again. Started with the first lesson. HTML, CSS, and Accessibility. Mostly basic stuff but I learned a ton about CSS. Last time I took a real look at CSS was in the early 2000s. It has changed a lot. I also enjoyed the section on accessibility. I also joined the [freeCodeCamp forums](https://www.freecodecamp.org/forum/) and helped a few people out. I really love the entire FCC and #100DaysOfCode community. Lastly, I submitted a few PRs to FCC itself. Specifically suggesting a new link in an intro guide and an updated link in the contributors guide.

### R1D2 5/6/2020
One of my PRs from last night was merged to freeCodeCamp which was a great way to start the day. I finished the responsive web design course on freeCodeCamp and started working on the first of 5 projects. I really like how FCC throws you right into the mix after giving you a brief introduction. The [Mozilla CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#Keyword_index) has been a godsend while I try to figure out how to do slightly more complex things with CSS. I also feel a bit more comfortable with grid/flex which I've always struggled with. 

### R1D3 5/7/2020
I spent too much time on the first project, building a [Tribute Page to Offer Nissim](https://levlaz.org/portfolio/tribute/). However overall I am happy with it. I should have taken screenshots along the way because this thing was a dumpster fire earlier today. The biggest things I was focusing on were properly using semantic HTML tags, and CSS. In terms of CSS, I *think* I finally kind of understand flexbox? I also took advantage of css variables, liner-gradients, and media queries. These are all things that I am not super comfortable with, but I am glad that I got them to work in this project. 

### R1D4 5/8/2020
I looked at the tribute page from yesterday on my phone and realized that it wasn't fully responsive on a mobile device. I think I am still a bit confused on how media queries and flexbox are supposed to work together. I got a slightly more polished version published today, but still not comfortable with this for now. I think the main issue is that I am trying to be fancy with my two columns. 

### R1D5 5/9/2020
I spent the day working on the [form project](https://levlaz.org/portfolio/form/) from freeCodeCamp. There are so many [HTML form input types](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input) that I didn't know about. I got stuck trying to add a validation message without Javascript. I'll revisit this in the future. I learned that the reason why my mobile responsive stuff wasn't working was due to me not including the [viewport meta tag](https://developer.mozilla.org/en-US/docs/Mozilla/Mobile/Viewport_meta_tag). I think I've taken it for granted that this appears to be built in to a lot of the frameworks that I've used. 

### R1D6 5/10/2020
I finished the [product landing page project](https://levlaz.org/portfolio/landing_page/) from freeCodeCamp. In this project I played around with some basic colors and limited myself to 1990s style web colors. It looks a bit cheesy, but I had a lot of fun with this one. I was able to use CSS grid and flexbox together in this one and it is finally starting to click a little bit.

### R1D7 5/11/2020
I finished the [technical documentation page project](https://levlaz.org/portfolio/docs/) from freeCodeCamp. In this project I got my sticky sidebar working with CSS grid without resorting to fixed positioning on the sidebar. CSS grid and flexbox are really starting to click with some of these "real-world" projects which feels really good. I'm hoping to wrap up the responsive design course tomorrow with the final project and then move on to the wonderful world of JavaScript.

### R1D8 5/12/2020
I started the final project in the responsive web design course on freeCodeCamp. I played with CSS gradients, and got the basic layout for the portfolio page completed. Tomorrow I will finish this project and be done with the first course on FCC. 

### R1D9 5/13/2020
I took a short break from FCC to scratch a different itch. I learned about the [relativedelta](https://dateutil.readthedocs.io/en/stable/relativedelta.html) library which makes it easy to get some pretty-ish looking years,months,dates between two dates. This is built into PSQL with the AGE function, but I didn't want my code to depend on a specific DB implementation. The added bonus is that I got to use the ternary operator in Python to print out the dates. I should write a brief post about this because my Googling didn't get me to far initially. 

### R1D10 5/14/2020
I wrapped up the responsive web design module on freeCodeCamp. Final project is a [portfolio](https://levlaz.org/portfolio/) that showcases all of the other projects I've worked on so far. Feeling pretty motivated. Looking forward to diving (back) into JS tomorrow. 

### R1D11 5/15/2020
I finished the basic JS module on FCC. For the most part this was a review of things that I already knew. The things that I found interesting in this course were case/switch, ternary operations, and recursion. Recursion is something that I've always struggled with, and today was no exception. 

### R1D12 5/16/2020
I finished the ES6 module on FCC today. It was a nice overview of the new featurs that ES6 offers. Most interesting things for me were new types of variables, arrow functions, destructuring, modules, and promises. 

### R1D13 5/17/2020 
I finished the regex course on FCC. This one was one of the trickier courses that I've done so far. I think I am miles away from where I started with Regex many years ago, but its always an area that I struggle with. The [Online Regex Tester](https://regex101.com/) is a godsend to test out and understand what is happening with regex. 

### R1D14 5/18/2020
I finished the debugging module and the first half of the data structures module on FCC. Mostly learned about all of the various ways to interact with Arrays. 

### R1D15 5/19/2020
I finished the data structures module and started working through the basic algorithms module.  

### R1D16 5/20/2020
I kept working through the basic algorithms module, but this one is kind of a slog.

### R1D17 5/21/2020
I took a break from JS and used the things I learned in the responsive web design course to build a very boring frontend for my Django version of ManagerManager. I think I am going to spend a few days tinkering with ManagerManager before diving back into Javascript.

### R1D18 5/22/2020
I spent some more time building out the basic structure of ManagerManager. 

### R1D19 5/23/2020
I wrote little code today, but spent a large portion of my time pouring through the Django documentation. 

### R1D20 5/24/2020
Used list comprehension, and played around with more generic Django views. Also started to use QuerySets properly and figured out how to report around self-refferential relationships. Overall, I got a lot done, but I get the sinking feeling that I am not doing things "the right way". 

### R1D21 5/25/2020
I migrated ManagerManager from sqlite to postgresql and deployed it to run on a server so I can access it from the outside world. I don't trust my own security enough to put it out in the world outright, so I am still accessing this via tunnel. 

### R1D22 5/26/2020
I added a bunch more models to ManagerManager and started working with more generic views. Generic views are a great concept and remove a lot of the boilerplate. They are not necessarily simple though. Its arguably a mistake to jump straight into class-based/generic views without fully understanding the underlying mechanics. However, I feel OK just pushing through. This is my 2nd or 3rd attempt at making ManagerManager work and I am more motivated by "good enough" software than "good software" at this point. 

### R1D23 5/27/2020
I went back to the JS course on FreeCodeCamp and finally finished it. It was so helpful to step away from it for a few days because I began to feel stuck and unmotivated. I came back with a fresh set of eyes and brain after working on the django app for a few days and knocked out the rest of the course. The [Arry.prototype.splice()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice) method is a bit tricky, and I ran into a bit of trouble with it, but after using it for a few of the challenges I think I finally got the hang of things. 
