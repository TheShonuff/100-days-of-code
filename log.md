# 100 Days Of Code - Log

### Day 0: April 25, 2022 

**Today's Progress**: Started my REACT Journey with a few challenges on [Free Code Camp](https://www.freecodecamp.org/learn/front-end-development-libraries/).

**Thoughts:** Since I have gotten better with Javascript I have been looking to learn REACT and this challenge has been a code way to get me motivated to get started. So far the concepts of JSX and components seem pretty straightforward. I look forward to finishing this Code Camp module so I can start a project. 

**Link to work:** N/A

### Day 1: April 26, 2022 

**Today's Progress**: Continued with[Free Code Camp](https://www.freecodecamp.org/learn/front-end-development-libraries/) and then did an extra hour of tutorials on udemy. 

**Thoughts:** About half way through the freecodecamp learning module now. Props were a little confusing at first but I seem to have a bit of a handle on them. Started learning States before I had to change tasks and start another project. I do have an idea of a project I want to tackle when I get a better grasp of the basics. 

**Link to work:** N/A

### Day 2: April 27, 2022 

**Today's Progress**: Mocked my project in Figma to get an idea of what the end result may look like. Discovered CodeWars today and spend a little too much time on one of the problems. Went through a couple of FreeCodeCamp modules and started a code along Pokdex project on uDemy. 

**Thoughts:** Discovered CodeWars through twitter today. The problems seem to be a little more beginner friendly compared to LeetCode. Worked through 3 problems and spent a lot of time on the binary to number problem. When I solved the problem I discovered it was solved in one line with parseInt. Which is a way more elegant solution then what I wrote. 

Finished an online connect form using nodemailer and multiparty for a website I'm making for a photographer friend. Struggled getting the modal to accept subject line specific to the item clicked. Solved the problem using subject.value =  rather than subject.textContent.

**Link to work:** [Draft Mock](https://www.figma.com/file/dlFy9yvgcgGhTAlGtXu93Z?node-id=0:1)

### Day 3: April 28, 2022 

**Today's Progress**: Not much on the javascript/react progress today. Been working on a photopgraphy website and got caught up on getting the portfolio page working. I was able to review notes on REACT components and props. I performed a couple of review exercises at the end of chapter 4 in Eloquent JS book.

**Thoughts:** Working on a client webpage and found a responsive plugin called masonry. I was able to install the plugin but was unable to get the application working correctly through node. I need a better understanding of importing/exporting modules. I found an application that can "roll-up" you're javascripts on deployment so they all work but I didn't understand the concepts fully. 

I spent too much time trying to get masonry-layout working today. I did end up achieving a product that is functional but outside what I originally set out to do. I have the script for masonry loading into a script tag on the page and calibrated bootstrap to handle the layout adjustments. After this project I probably will never use bootstrap or some sort of framework for CSS ever again. 

**Link to work:** n/a

### Day 4: April 29, 2022

**Today's Progress**: It's Friday but my Monday at work. Today I'm tired and only did the minimum 1 hour. I worked through the final bit of exercises of chapter 4 in Eloquent JS and ran a few CodeWars.

**Thoughts** It seems to there is so much too memorize and remember when solving some of these code war problems. I often make silly mistakes in my function writing which leads to extra time debugging. 

### Day 5: April 30, 2022

**Today's Progress**: Busy day at work today but still managed to log almost 3 hours of computer time. A good chunk of my time was spent trying to figure out how I broke npm. I *was* using npm with [SUDO](https://docs.npmjs.com/resolving-eacces-permissions-errors-when-installing-packages-globally) and finally made the change to get off of that. At first nothing was working in my terminal which was fixed after closing my terminal session. Then I need to point my shell to the new path. 

After that headache I was able to deply a site I was working on to start developing an instagram basic view but realzed how broken the site is still so I'm gonna go back and start going through the bugs tomorrow.

I then logged 1 hour on uDemy finishing a REACT code along. Then I started working through a Mongo/Express demonstration. 

**Thoughts** Need to start practicing this tutorials more. I'm starting to get a sense the information is not really sticking well. 

### Day 6: May 1, 2022

**Today's Progress**: Did the minimum amount of work required today. Between a busy day and work and an early day tomorrow I decided to take a semi-rest day. I discovered notion and began importing all my notes over for easier access. I then did a couple of codewars problems and looked into Bundlers.

**Thoughts**: I am having trouble choosing a javascript bundler. There are a few options with Webpack, Rollup and Parcel being the most popular choices. However they all seem to take different approaches. Based on the summary at [bundler report](bundlers.tooling.report) I might be choosing between Parcel or Webpack. I need to grok what's happening in the package.json scripts section to unlock how these work. 

### Day 7: May 2, 2022

**Today's Progress**: Wrote my final lab for ELE 181 in C++ today. Was a relatively easy assignment that combined all the lessons into one lab. After learning Python and Javascript this was a very easy lab to perform. I then moved on to learning more about React state and props. Finished a couple of FreedCodeCamp modules.

**Thoughts**: Feeling more confident in understanding state and props. I need to go back and understand further callbacks and arrow functions. I seem to shy away from using them probably because I don't fully grok the callback. 

### Day 8: May 3, 2022

**Today's Progress**: Did some debugging for the ooh la la site. I was able to solve some of the problems but the main issue of enabling the masonry feature AFTER the site has finished loading is still alluding me. I've taken further steps to understand import vs require and started learning about Webpack and how it may help me solve this problem. 

**Thoughts**: Kinda frustrated that I'm having a tough time understanding imports and require and why I can't just simply import a library and write a function to activate it on when the window loads. I'm really trying to avoid using jQuery as well to solve this problem. is that a good idea? 

### Day 9: May 4th, 2022

**Today's Progress**: Pretty happy about today. I was able to fix the mansonry loading issue by using webpack to create a file that directly uses the nodule module through an import and create a bundled file that I directly imported to the webpage through the script tag. I Then moved on to tackling some REACT tutorials and began working on the FrontEnd mentor Github User Search api. I was able to get a fetch request working correctly based on the from input. Unsure of how safe it actually is though.

**Thoughts** React might be way overkill for this frontend mentor project but it's good that I'm getting my feed wet with the material. There are certainly some confusing aspects of REACT like not having to define a function before writing a function... but I guess that's because it's actually a method. Remember they're objects you're working with. Overall happy with today's progress. 

### Day 10: May 5th, 2022

**Today's Progress**: Another productive day on the coding front. Solved all the major issues with Ooh La La photography site and waiting for feedback. Wrote a length blog post about my dealing with Webpack and tackled my Front End mentor challenge with the github api. I've jumped the major hurldle with the application with getting the JSON loaded and rendering to the DOM. Now all I have to do is style the damn thing. 

**Thoughts** feeling good about my progress today. I did try to setup my development configuration a bit further today by attempting to automatically write a new webpack bundle on save AND re render my browser. I was able to get the webpack part working but the second half seems confusing. 

While writing my REACT app I'm wondering if I'm over complicating it. I tend to do this a lot with things but I'm not well enough versed to know I'm taking the long way around. I'm writing all my components using class components as opposed to functional components. It's just the way I learned I guess but at this moment it seems more natural or at least the only way I can reliable setup a component in REACT. 

P.S I don't think I like CSS very much... 

### Day 11: May 6th, 2022

**Today's Progress**: Day spent mostly wrestling CSS. I did manage to get the search bar styled and the top-half of the user results view styled. 

**Thoughts** I kinda dislike CSS right now. I know I have to keep at it and try to learn the concepts but I really can't seem to get the elements to play nicely on the screen. It takes a lot of time to figure out how to align everything properly. Started back with the basics for note taking and added some cards to Notion for reference in the futre. I'll get this shit...sometime soon hopefully. 

P.S still hate CSS

### Day 12: May 7th, 2022

**Today's Progress**: Kicked the day off prototyping a project that I'm interested in doing. I modeled the DB schema and the UI. The project seems pretty straight-forward to get a MVP. I then moved to more CSS on the REACT git-hub user API search. Learned the componentDidMount function to call an event when the object is activated. When the app loads the search component it will automatically fetch the OctoCat profile from github and display that rather than a blank screen.

**Thoughts**: Still hate CSS but it's getting better slowly. Learned how to group items a little better for some efficiency. Starting to get a better feel for Flex and managed some decent progress on the UserView component. The componentDidMount is a pretty useful method? Function? It's actually a Class Definition.... Just googled it. Progress is made gotta start getting comfortable with MongoDB. 


### Day 13: May 8th, 2022

**Today's Progress**: Mellow day. I'm super tired. Took it slow and styled my Front end Mentor App. Figured CSS grid was the best approach for solving a few UI elements and it was. I kinda get CSS grid now. I need to setup a lot of IF statements it seems based on the state of my props coming over from the search component.

**Thoughts**: Wondering the most effienct way to conditionally setup styles and outputs in react. There are a number of props being passed to the Userview that could potentially be NULL and I would need to setup the resulting output and corresponding style. Should the variable reflect both the style and output for ease? Like an object perhaps? 

### Day 14: May 9th, 2022
 
 **Today's Progress** Not much. Wrestled with REACT in trying to get a state to persist when I get an undesired result from a search query. I can get the error message to display but the props that were set previously all go to NULL. 

 **Thoughts** Had to study for finals and look at other items tonight. unable to really focus.

 ### Day 15: May 10th, 2022

 **Today's Progress**: Solved my previous issue with REACT. Was able to set a way for the Render to NOT update based on a condition. Then I figured out I had to set that condition in a CHILD as setting the condition in a parent affects the whole tree. Then I attempted some additional styling of the app and managed to deploy the app on Netlify. Tomorrow I'll work on getting the date to format correctly. The tricky part is going to get the month to match up correctly to what I get in the JSON response. There's a zero leading numbers less than 10 and REACT was already upset setting my object to keys as 01,02,03 etc. 

 **Thoughts** Getting more comfortable with React Class components. I'm seeing that functional components are better but I'm not sure how to pivot out of the hole I'm already in....

 ### Day 16: May 11th, 2022

 **Today's Progress**: No real progress today. I had a final exam that took up a lot of time. I spent the rest of my time researching how to toggle light/dark mode in the Application and didn't come up with any good solutions. I tried to install Tailwind CSS but I got a ESline error and I ran out of time debugging the issue. I suspect using Tailwind this late in the styling game isn't a great idea. I need to figure out how to toggle between themes so other way.

 **Thoughts**: FUCK CSS... seriously. 

 ### Day 17: May 12th, 2022

 **Today's Progress"** Started project CIS implementation today. Created the frontend and backend project. I installed mongo, express and seeded the database. I successfully posted a get request and received a json response. Will work more on the backend before tackling the frontend of the project. On the Github user search app. I failed to get the media queries to work correctly. My iphone doesn't seem to load the right media query but it looks fantastic in the Firefox testing port. Fuck CSS

 **Thoughts**: excited about project TIS. Will not touch front end stuff until I finish the github user search app and have most of the back end get requests done. I need to also work on a admin page to input data into the data base. 

 ### Day 18: May 13th, 2022

 **Today's Progress** Successfully parsed my Date string from the JSON and now have a date string that looks like the design. I also successfully have working media queries for the ipad and iphone. Also spent about 40 minutes studying MongoDB for an upcoming project. Need to seed my database with more entries for experimentation. 

 **Thoughts** The media queries are working as expected now. I increased the max-width size and remove the only operator and it seems to be working fine. now sure how increasing the max-width solved my issue immeditaely but it's working as expected. Parsing the Date string was pretty straight forward. I moved my list of Months from an Object to an Array and filled the first position with a "null" as no date will return a 00. I then used the infamous parseInt() to shave the leading zero and used the new variable as my index. I hope my if statement within my function is enough for checking against possible errors. Time will tell.   

 ### Day 19: May 14th, 2022

 **Today's Progress**: really tired today and not much accomplished as I'm calling it early to go to bed. I was able to use the ternary operator to achieve conditional styling in my Github User Search app. I touched up a few styling issues and moved onto seeding my TIS database so I can have some content to play with to make sure my schema is strong enough.

 **Thoughts**: Need to start thinking about the light/dark theme button on my Github app as that's the last major hurdle until it's completed. Mongodb seems pretty simple so far as I seed the database and make queries. I'll need to figure out how I want my get requests to return. 

 ### Day 20: May 15th, 2022

 **Today's Progress**: Succesfully implmented Theme changing!!! This trick was is [data-theme]. I tried writing a function to change the style directly in the app.js by toggle a button between 1 and 0 and having the class set based on the toggle condition but I didn't have any luck. A tutorial was able to guide me in the right direction.

 **Thoughts**:Feels good to have this almost done and move on to something else. Just need to style the theme button tommorrow. That should be interesting. 

 ### Day 21: May 16th, 2022

 **Today's Progress**: Finished the github search app from front end mentor. Granted there are several html errors and maybe some styling issues none the less it's considered finished. I'm moving on. Started some React exercises in Udemy to further drive home Props and State. Need to get this up to muscle memory. I'm forgetting a lot small things.

 **Thoughts**: Feel good about how I'm progressing. Getting more comfortable with CSS and React. Can mostly setup projects with little note referencing. This get mixed up with how to lay out my components and who's leading who.

 ### Day 22: May 17th, 2022

 **Today's  Progress**: Mellow day. Only watched a few uDemy classes and did 2 exercises. Finished the day with a codewars 

 **Thoughts**: Got confused in setting up a project and didn't attribute this correctly. Learned a few new methods for event binding that I'll watch for in the future.

 ### Day 23: May 18th, 2022

 **Today's Progress**: Productive day. Managed to do a code along and get a grasp of Firebase. Utilized login and database entries.Connected TIS app to MongoDB Atlas and was able to successfully get data from a request. Outline some UI components in the TIS app. Started and styled a new frontend mentor app. 

 **Thoughts**: Spent too much time today getting stumped on array's of objects in React. Seems to be that I need to use map to go through embed items. Even on a FindOne one search request I had trouble reading the document that had an embed layer? I forgot the proper term. I would need to access view Data.Layer.Layer2 and React get's upset every time even though a console.log show it understands that it's an object. 

 Feeling good finishing up today with my CSS skills. Was able to mostly layout the next frontend mentor project. Need to hook up the logic tomorrow. It's mostly done though. I was able to hook to onChange events to the input field and the app see's the state change in real time. I just need to write the methods to perform the math functions. 

 ### Day 24: May 19th, 2022

 **Today's Progress**: First skills assesstment test while in the new job market. Edited some issues with the Github user search app. Finished the Logic in the Tip calculator. Some minor styling issues remain.

 **Thoughts**: Got burned on some dynamic styling in the github app. That in combination with the after thought that is the theme-toggler button which sits outside of EVERYTHING. So it's not affected by any adjustment of the views below it. If I understood hooks better I might be able to throw it into the search component but I didn't have any luck when I tried it earlier. Maybe I'll make a git branch and try it for real after I get a better grasp down the road...

 ### Day 25: May 20th, 2022

 **Today's Progress**: Tried to make sense of SquareSpace templating. Didn't make any real progress other than setting up a dev enviroment on the local machine. Worked on the Tip calculator challenge some more. Was hoping to finish but got stumped on a few styling challenges. Logic is completely done. 

 **Thoughts**: Was hoping to get the Tip Calculator finished but spent a lot of time trying to get a dynamic outline for an error of zero people selected. which I think is a crap design. There would be no situation where 0 people would be selected for calculating a tip. There would always be at least 1 person dining. Defaulting to 1 person makes the most sense. I get that it's a challenge to display a certain style if an incorrect input is selected but zero people would almost never be selected unless by mistake. Anyways. The styling on desktop is done and now to move onto getting the table and mobile done.

 ### Day 26: May 21st, 2022

 **Today's Progress**: Installed new keycaps on keyboard and finished the frontend mentor challenge. Calling it early today to catch up on some rest.

 **Thoughts**: feel silly for not knowing that I can view the development site on my phone by navigating to my local ip:port... Made mobile styling WAY easier.

 ### Day 27: May 22nd, 2022

 **Today's Progress**: No real progress today. Spent some time working on C++ and flashed micro-controller to work with WLED

 **Thoughts**: Going to bed early and get some sleep.

 ### Day 28: May 23rd, 2022

 **Today's Progress**: Feeling tired. Did a uDemy exercise completing a hangman game and then move on to some codewars.

 **Thoughts**: Weather is getting hot. Really tired lately and can't focus. 

 ### Day 29: May 25th, 2022

 **Today's Progress**: Some small progress Today. It's my day off and it's summer time so I find my energy levels pretty low. I was able to complete the Lights out game on uDemy and finished the Forms module. Spent some reading reading trying to fully grok the map method. Seems really important to grasp this method for when I using react.

 **Thoughts**: The forms module was pretty easy and I had discovered alot of the material covered when I was working on the tip calculator application for front end mentor. I might go back and try to refactor the application based on learning how to pass data upwards but we'll see how motivated I am. I just might keep it in the back pocket for when I designing the next project as I have a better idea how to break up components and pass data around. 


 ### Day 30: May 26th, 2022

 **Today's Progress**: Performed and completed 2 exercises from the Colt Steel udemy class. Getting a solid grasp of passing data around and reading code

 **Thoughts**: Feeling more confident in writing React logic. I'm starting to find some more gaps in things I need to learn. Like a better understanding of creating and defining custom objects. There was a point in the Yahtzee game application where there was a custom rule set and I didn't understand all the written code.

 ### Day 31: May 27th, 2022

 **Today's Progress**: Finished the Yahtzee exercise. Was starting to get frustrated with the using of class components as I'm seeing that most of the dev community has moved away from class components to functional components so I skipped a few modules to begin the work on functional components. 

 **Thoughts**: Still finding those gaps. Which is good. I know I need to focus on understanding callbacks better and certain array functions like map. I did learn about the Object method of SET today. Which is why I noticing this gaps. I wonder what the best way is to remember some of this important ones and be able to pull them down from memory??

 ### Day 32: May 28th, 2022

 **Today's Progress**: Some more time in Udemy learning about functional components in React. I plan on finishing out the next exercise and then begin working on project to implement what I have learned. I ideally I would like to get to the next.js part before I begin so I can start implementing next but I feel I have a couple of more days ahead of me before that can happen.

 **Thoughts**: Functional components continue to prove themselves to be way better to write and use. 

 ### Day 33: May 29th, 2022

 **Today's Progress**: Light day. Have work early tomorrow. Did a couple of codewars fundamentals and then started the Hooks project on uDemy. Played with Material UI

 **Thoughts**: Looking forward to finishing this exercise on React Hooks so I can start a project. The concepts are clicking with me. Material UI is interesting to use in React. Seems complicated with all the extra imports to just avoid some CSS. 

 ### Day 34: June 1st, 2022

 **Today's Progress**: couple day break. Summer class started and needed a few rest days. Wasn't able to tackle much today. Did a few codewar problems and tried to finished the last of uDemy react Bootcamp on functional components before tackling projects to have a solid understanding.

 **Thoughts**: Looking forward to start implementing some of these fun things I'm learning. usecontext, useEffect.

 ### Day 35: June 4th, 2022

 **Today's Progress**: Started the frontend Mentor Tic-Tac-Toe Challenge. Got the basic structure outline in React and the components setup. 

 **Thoughts**: Certainly harder than expected. First major hurdle is rendering the board with individual "square" components and having those square components update the State based on a Click. I'm currently able to set each square with a Key but at integer doesn't register with any click events. Will spend time researching tomorrow before I tackle again.

### Day 36: June 6th, 2022

**Today's Progress**: Continued the tic-tac-toe challenge after school work was completed. Managed to update the state and render a symbol to reflect that state change. 

**Thoughts**: This project is challenging. I'm out one my own with no tutorial to follow so I'm kind having to piece everything together and search for the snippets I need for this project. Wanted to give up and move to something easier but I realize this is how you learn. I find it curious how X,Y are flipped in certain parts of the functions....


### Day 37: June 7th, 2022

**Today's Progress**: More Tic-Tac-Toe challenge. Was able to make some good progress. Added alternating player changes after the board is updated. Able to reset the game and can detect the winner if a row meets the qualifications. 

**Thoughts**: I suspect a major issue I was having was over thinking the problems. Once I was able to get something written down I was able to move the functions around to work in my favor. good progress today. Feeling better. 

### Day 38: June 8th, 2022

**Today's Progress**: A lot accomplished on the tic-tac-toe app. Game Select state done. Majority of the logic and started to implement the game won modal.

**Thoughts**: Things are making sense. It will be interesting to see where I can refactor this application using context and useEffect. 

### Day 39: June 9th, 2022

**Today's Progress**: Still making good progress on the tic-tac-to app. Ran into an issue with how styles are applied when the modal is active. I would like the background to dim to bring focus to the modal but an opacity attribute is applied to everything. There are a few things left to do on the project and they're all mostly styling related. Need to set the squares to be highlighted during a win condition. Need to make a modal for the Tie or Draw condition. And need to setup the CPU player and allow the picking of symbols for player one. 

**Thoughts**: 2 steps forward 1 step back. Feeling good that things are making sense but right when you get a groove going you're smacked with a new challenge and you feel that you're not smart enough again to solve the problem. Hopefully some refelection on the problem will bring forth a solution.