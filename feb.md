# february

**wednesday, 2023-02-01**
<br>
had a townhall meeting where the CEO presented the new project my squad has been working on to the entire company: we acquired it is an ecommerce builder company (dlojavirtual.com). i am happy to see the acquisition, being that many other companies are doing hardcore layoffs and slowing down, it seems that we are expanding.  
<br>
<br>
<br>
**thursday, 2023-02-02**
<br>
spent most of my day asking and understanding the PHP code on the email task, and how it relates to WHMCS. got some tips, but could only accomplish it after a 5 min call with a senior. as it is a different project and language, i don't feel too bad. ended up making the code correct and moresimple. big win.
<br>
<br>
<br>
**friday, 2023-02-03**
<br>
spent my morning solving issues with my PHP PR. i didn't have the permissions to push any code to this repo. my senior gave me permissions, still nothing. contacted devOps, and it was a local issue. solved by > sudo chown ${USER} -R on the correct directory. meeting combo: monthly engineering meetup + gator class, where people share updates on their projects and technology choices. solved two simple tasks. i currently feel more productive at the office than at home.
<br>
<br>
<br>
**monday, 2023-02-04**
<br>
i can't remember a single thing from this day. **mondays are rough.
<br>
<br>
<br>
**tuesday, 2023-02-05**
<br>
worked with a colleague to add datadog functionality to the new site. the idea is to monitor success|failure on login|signup forms. learned a lot about docker, makefile and next.
<br>
<br>
<br>
**wednesday, 2023-02-06**
<br>
launch day for the new site dlojavirtual.com. war room from 7AM to noon. as convenient as the idea sounds, it's too much time for too little value. 30+ people for 5 hours is expensive. half of them provided no comments or help. some developers of the acquired company showed up. interesing to see this as the first contact between us. we handled minor production incoveniences during deploy.operation ended up being declared succesful around 2PM.
<br>
<br>
<br>
**thursday, 2023-02-07**
<br>
worked on a bug that disallowed the opening of a new tab as an async operation in javascript. this we found a bug on the new site: when a login form was submitted, we opened a link on the same tab. this caused certain google analytics events not to trigger. decided to open in a new tab instead. but browsers by default block opening a new tab as an async operation. this link was interesting: https://www.abeautifulsite.net/posts/opening-a-new-window-after-an-async-operation/
<br>
<br>
<br>
**friday, 2023-02-08**
<br>
top down demands for the new site. overall layout and content clarity improvements. added help text to every CTA on the home page of dloja to remind users that they don't need to give credit card info to signup for our trial. replicated these changes to hostgator.com.br/loja-virtual. ** friday deploy. yolo.
<br>
<br>
<br>
**monday, 2023-02-13**
<br>
0.10mbps internet connection all day. did some leetcode problems I had saved locally. available at https://github.com/LukeberryPi/leetcode
<br>
<br>
<br>
**tuesday, 2023-02-14**
<br>
slow internet in the morning still. attended the daily meeting through my phone 4g. went to aunt's in the afternoon. got assigned a security/compliance task: on two of our sites (hostgator blog and hostgator guide), there is a search bar which is an input, and currently is not sanitized. this means that, if you input HTML, it will render to the page. this could be used with malitious intent, and shall be fixed.
<br>
<br>
<br>
**wednesday, 2023-02-15**
<br>
worked on the security fix for two projects: hostgator blog and hostgator guide. thought i found the fix by sanitizing the input onChange (where the state is declared). this didn't fully work. later found out that this string had to be sanitized when it is displayed to the screen.
<br>
<br>
<br>
**thursday, 2023-02-16**
<br>
got into working at a refactoring task: the Typography component of the new project must be refactored. the idea is to create a TypographyV2 component, and slowly deprecate the old one's use. deployed hostgator blog and hostgator guide after going back and forth with DevOPS for a while over the security injection task.
<br>
<br>
<br>
**friday, 2023-02-17**
<br>
more refactoring of typography. spent some time searching through styled-components documentation looking for a way to set the html tag for a given component dynamically. found the "as" prop, which works exactly as intended. the goal is to tie text styling to figma naming, so that adding new text is less error-prone (and no media queries needed for responsive sizing).
<br>
<br>
<br>
**wednesday, 2023-02-22
<br>
everyone is back from brazilian carnival. slow day.
<br>
<br>
<br>
**thursday, 2023-02-23**
<br>
started redesigning planCards on ecommerce website https://dlojavirtual.com/planos. adjust height of all 3 cards to be the same, adding features and altering copy. updating price formatting, currency overhead, price middle, cycle baseline.
<br>
<br>
<br>
**friday, 2023-02-24**
<br>
continued. i like this design. turns out to be a lot of work, especially after some rounds of validation. react-slick isn't setting the carousel width correctly, generating differences between figma and my code. took a good while on this.
<br>
<br>
<br>
**monday, 2023-02-27**
<br>
rushed final layout changes to be deployed today. broke production. i took too long to realize and people had to step-in for me, bad feeling. personal note to be more dilligent about deploys and chat messages.
<br>
<br>
<br>
**tuesday, 2023-02-28\*\*
<br>
fixed prod issue in the morning. redeployed mine + others tasks in the afternoon. double attention. worked on a domain list ordering task for ES domains on the mainsite. learned about passing parameters through a URL.
<br>
<br>
<br>
