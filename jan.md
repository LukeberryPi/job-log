# january

**monday, 2023-01-02**
<br>
first monday of the year. two big lessons: using absolute positioning is a bad idea and a focused 2-hour session on monday is more productive than the entire friday afternoon. finished developing the step by step component on a new company projectafter being stuck since last year. flexboxes, flexboxes everywhere.
<br>
<br>
<br>
**tuesday, 2023-01-03**
<br>
a ghost from the past took away most of my day. minor content adjustments from an older task to be deployed tomorrow. reduced scope so it could get through in time. started developing a dropdown component for the new company project. negotiated working hours for tomorrow, since i'll be travelling back to florianopolis.
<br>
<br>
<br>
**wednesday, 2023-01-04**
<br>
nothing but buses, traffic, uber and planes. thought i'd be able to work a few hours in the afternoon, but i arrived too late.
<br>
<br>
<br>
**thursday, 2023-01-05**
<br>
continued development of select component (renamed from dropdown). had a hard time typing an onClick function in React + TypeScript. FormEvent and MouseEvent lead to "no overload matches this call". called for help, we couldn't get around it and opted for a cheeky any + eslint disable.
<br>
<br>
<br>
**friday, 2023-01-06**
<br>
spent time styling an refactoring the select component. got familiar with passing onClick functions as props to react components. onClick && onClick(). created state for isOpen, as well as logic for toggling onClick and handleOutsideClick + eventListener. sent PR.
<br>
<br>
<br>
**monday, 2023-01-09**
<br>
my pr was unapproved: any not allowed! turns out the event should have been typed MouseEvent instead of React.MouseEvent. fixed this and refactored some import/exports around the repo.
<br>
<br>
<br>
**tuesday, 2023-01-10**
<br>
suffered with terrible internet in the afternoon. ended up doing mostly content edits and code reviews.
<br>
<br>
<br>
**wednesday, 2023-01-11**
<br>
welcomed back my PM (from vacation). asked for new tasks since the ones I had were blocked. got assigned two simple tasks on another project. took time to set up that project, do 1 task and start developing a new component: a top bar! (might be seen on https://hostgator.com.br ocasionally)
<br>
<br>
<br>
**thursday, 2023-01-12**
<br>
did most of the logic for the top bar. getting familiar with props and their types. this project uses typescript. it feels like a hurdle at first but very pleasant after a while. except for typing click functions. created props for top bar title, link and behavior open in new tab behavior: window.open(target, openInNewTab ? '_blank' : 'self').
<br>
<br>
<br>
**friday, 2023-01-13**
<br>
getting habituated with asking questions more frequently: was unsure how to unit test a component in jest + React Testing Library. it's a generic top bar component that receives a link, and I am testing the onClick behavior. but i don't pass it an onClick prop? i was oriented to use Object.defineProperty on global object, add a location property and assign it a link.
<br>
<br>
<br>
**monday, 2023-01-16**
<br>
got assigned a simple css fix. done in minutes. waiting for validation. extra meetings besides daily, to align priorities and refine our focus during Q1 2023. had no tasks for a while after lunch, got called out (don't do this). rescued an incomplete task from December.
<br>
<br>
<br>
**tuesday, 2023-01-17**
<br>
css fix validated. pr reviewed instantly, since it was a one-liner. managed to squeeze this change into today's deploy. win. meeting addressing some paradigm shifts in our engineering culture. focus is moving away from one-team === one-product towards one-team === macro-goals. more on this soon.
<br>
<br>
<br>
**wednesday, 2023-01-18**
<br>
even more meetings, busy week. ubuntu 20.04 is crashing three to five times a day, forcing a laptop restart + vpn reconnect, teams reconnect and e-mail reconnect. my workflow is terrible right now.
<br>
<br>
<br>
**thursday, 2023-01-19**
<br>
got assigned a very exciting accessibility task for the new project. basically hunting improvements to increase pagespeed score. learned how to get insights for performance and accessibility in a VPN protected url and localhost as well.
<br>
<br>
<br>
**friday, 2023-01-20**
<br>
adding alts, renaming links and overall accessibility improvements. very interesting meeting by the afternoon to address some of the squad challenges for Q1. very technical and challenging to follow.
<br>
<br>
<br>
**monday, 2023-01-23**
<br>
tinkering with accessibility insights. had a few back and forths with the PO on the table task. ultimately approved. unapproved right after by tech lead. severe disalignment issues. after a few hours of trying + asking for help, he told me that it is a simple react-slick change: slidesToShow={3} => slidesToShow{2}, since I ported this table from another page with 3 columns but this one has only 2.
<br>
<br>
<br>
**tuesday, 2023-01-24**
<br>
PR for accessibility got denied. i hard coded the aria labels + wrote them in English. it would be ideal to receive them from each page's content, so that it is relevant for Mexico, Colombia and Chile users. we operate in these 3 countries besides Brazil.
<br>
<br>
<br>
**wednesday, 2023-01-25**
<br>
planning at 9AM. it will be a relatively relaxed sprint for the front-end team, we are below capacity. this might + will change in the coming days. ended accessibility task + table addition task. heading into accessibility 2: the return of the king. this one has the changes that I couldn't make in time in the last task. 
<br>
<br>
<br>
**thursday, 2023-01-26**
<br>
tweaking of the accessibility task and the table task. yet to be approved. i will present our new project alongside a colleague next **tuesday**. quick chat with him in the afternoon. what, why, when and how will this new project impact our company? these are the answers i want to answer.
<br>
<br>
<br>
**friday, 2023-01-27**
<br>
2 of my PRs that were pending got approved! got assigned a task to update the skeleton (loading) layout for another product. had a front-end guild meeting at 3PM, showed up on time. got cancelled due to  insufficient quorum, overall a slow day.
<br>
<br>
<br>
**monday, 2023-01-30**
<br>
skeleton PR approved. handled a mainsite deploy by myself for the first time, under supervision of a senior and a junior colleague. had complications. some tests failed, but i got oriented to deploy anyway, under the assumption that it was a network mistake. turns out it was a modal component blocking clicks on an entire page. had to implement adjustments, reapprove PR, and restart the incomplete deploy. this cycle repeated a few times, leading to a 2-hour delay on the deploy.
<br>
<br>
<br>
**tuesday, 2023-01-31**
<br>
opened the first production PHP code of my life. i have heard severe prejudice about this language. i have never touched object-oriented code ever, personally or professionally. looks scary. i have a task to fix a count of "0 years" on an e-mail that we send to clients who register a domain.