### february

#### wednesday
#### 2023-02-01

had a townhall meeting where the CEO presented the new project my squad has been working on to the entire company: we acquired it is an ecommerce builder company (dlojavirtual.com). i am happy to see the acquisition, being that many other companies are doing hardcore layoffs and slowing down, it seems that we are expanding.                              


#### thursday
#### 2023-02-02

spent most of my day asking and understanding the PHP code on the email task, and how it relates to WHMCS. got some tips, but could only accomplish it after a 5 min call with a senior. as it is a different project and language, i don't feel too bad. ended up making the code correct and moresimple. big win.


#### friday
#### 2023-02-03

spent my morning solving issues with my PHP PR. i didn't have the permissions to push any code to this repo. my senior gave me permissions, still nothing. contacted devOps, and it was a local issue.  solved by > sudo chown ${USER} -R on the correct directory. meeting combo: monthly engineering meetup + gator class, where people share updates on their projects and technology choices. solved two simple tasks. i currently feel more productive at the office than at home.


#### monday
#### 2023-02-04

i can't remember a single thing from this day. #### mondays are rough.


tuesday
#### 2023-02-05

worked with a colleague to add datadog functionality to the new site. the idea is to monitor success|failure on login|signup forms. learned a lot about docker, makefile and next.


#### wednesday
#### 2023-02-06

launch day for the new site dlojavirtual.com. war room from 7AM to noon. as convenient as the idea sounds, it's too much time for too little value. 30+ people for 5 hours is expensive. half of them provided no comments or help. some developers of the acquired company showed up. interesing to see this as the first contact between us. we handled minor production incoveniences during deploy.operation ended up being declared succesful around 2PM. 


#### thursday
#### 2023-02-07

worked on a bug that disallowed the opening of a new tab as an async operation in javascript. this we found a bug on the new site: when a login form was submitted, we opened a link on the same tab. this caused certain google analytics events not to trigger. decided to open in a new tab instead. but browsers by default block opening a new tab as an async operation. this link was interesting: https://www.abeautifulsite.net/posts/opening-a-new-window-after-an-async-operation/


#### friday
#### 2023-02-08

top down demands for the new site. overall layout and content clarity improvements. added help text to every CTA on the home page of dloja to remind users that they don't need to give credit card info to signup for our trial. replicated these changes to hostgator.com.br/loja-virtual. #### friday deploy. yolo.

