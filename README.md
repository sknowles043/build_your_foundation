# Build Your Foundation
Notes on how to build your knowledge, skills and experience in a demonstratable way.

# Your Focus
1. LEARN - **Learn Useful Skills** that will help you get a job and then be successful in that position.
2. BUILD - **Build/Create Stuff with the skills you learn.**  Experience going from idea to working functionality.
3. SHOW - **Demonstratable/Documented Results/Effort** so others can see your work.

## Step One - [Knowledge Management](https://en.wikipedia.org/wiki/Knowledge_management)
Choose a way to manage your knowledge, work, thoughts in some kind of wiki like software. 
This is central to organizing your efforts in a way that you can rely on, but is also something to show your work.

#### Wiki Software
- [Obsidian](https://obsidian.md/)  - Online, Free For Personal Use
- [Notion](https://www.notion.so/product) - Online, Free For Personal Use
- [TiddlyWiki](https://tiddlywiki.com/) - Offline, Can Be Online, Funny Name, Geeky, Powerful
- [Article with other wiki options](https://zapier.com/blog/best-notion-alternatives/)

This will be home to your notes, your investigations, your projects.  

### Too Many Choices!!! What is the BEST/RIGHT/OPTIMAL Choice? 
__3 hours later, 15 review/opinion videos viewed, 5 articles read, still no decision!__

There will be many times where you have multiple options and might fall into analysis paralysis about which is the right/best way/choice.

A good habit to get into is time box your decision.

Give yourself a fixed amount of time, use that time to investigate and then choose which ever you feel best about.

Probably the majority of the options you are looking at are very similar and you can be successful with any of the options before you.

Remember: [Perfection Is The Enemy of Good](https://en.wikipedia.org/wiki/Perfect_is_the_enemy_of_good) 

Also the enemy of progress and actually accomplishing anything. 

Getting something working (even if accomplished in a totally horribly way) is more important that a perfectly created but incomplete/non-working effort.

A very successful game [Undertale](https://en.wikipedia.org/wiki/Undertale#:~:text=The%20game%20sold%20over%20one,greatest%20video%20games%20ever%20made.) which solds millions of copies has one of the [worst code bases and is generally unmaintainable](https://www.reddit.com/r/programminghorror/comments/10dgoxm/til_that_all_of_undertales_dialogue_is_handled_in/).
Yet people loved that game and still love it.  

## Step Two
Get yourself a [GitHub Account](https://github.com). 

It is free and this will be where you place your efforts, that can be shared with anyone interested in your work, like potential employers.
When you decide to investigate something, do a tutorial, build a project, instead of the code/config/stuff just sitting somewhere put it in GitHub.

GitHub is probably one of the most widely used [version control](https://en.wikipedia.org/wiki/Version_control) software out there and will be a part of your career.

Take the time to look of the [GitHub Docs](https://docs.github.com/en)

The [git](https://en.wikipedia.org/wiki/Git) in GitHub is the underlying software for managing versions and is a command line tool. More on learning to use command line later.

Take some time to look into various git tutorials out there [W3 Git Tutorial](https://www.w3schools.com/git/) , [SCM Git Tutorial](https://git-scm.com/docs/gittutorial)

## Step Three - Choose A Project
Start with something small. Re-create something that someone else has done or find something that would help you in your daily life. Keep the scope small for now.

Something that might take a few weeks, not something that can be accomplished in an afternoon.

One of the goals of the project is to give you reasons to learn/use a wide range of technologies.

As an example, Create A Running Website where you can enter an Actors Name and see the list of all movies, tv they have been in.
Wait, isn't that just [IMBD](https://www.imdb.com/).  Yes it is but your website will be just 

```
Actor Name: [  TEXT BOX ] [Button: SEARCH]
```
Like all projects, take the idea and start breaking it into pieces.  Then break those pieces into pieces until they are small enough to work and accomplish in a reasonable amount of time.

So we need a way to get a web page, that talks to a server that can then access data about actors.

Web Page -> Look into [React](https://react.dev/) or one of the [alternative frameworks](https://www.sitepoint.com/exploring-the-top-lightweight-alternatives-to-react-in-2023/)
  This means you will need to learn [JavaScript](https://www.javascript.com/) or [TypeScript](https://www.typescriptlang.org/), [HTML](https://www.w3schools.com/html/), [CSS](https://www.w3schools.com/css/)

Server -> Depending on Language, lots of options to build a server.  [Python](https://pythonbasics.org/webserver/)  [C#](https://learn.microsoft.com/en-us/troubleshoot/developer/visualstudio/csharp/language-compilers/create-remote-server) [Java](https://www.codeproject.com/Tips/1040097/Create-a-Simple-Web-Server-in-Java-HTTP-Server)
  I do recommend learning [Python](https://developers.google.com/edu/python) and at least doing tutorials in either [C#](https://www.codeproject.com/Tips/1040097/Create-a-Simple-Web-Server-in-Java-HTTP-Server) or [Java](https://www.tutorialspoint.com/java/index.htm)
  I also recommend using [VSCode](https://code.visualstudio.com/) as your [IDE](https://en.wikipedia.org/wiki/Integrated_development_environment).  There are many IDEs out there, but that is one of the most flexible and can be used for any language/project you choose to work on.
  The server will get a request from the Web Page, make a call to the persistence and return the list of result to be displayed on the Web Page.

Data Persistence -> Need a place to put data and retrieve data.  There are lots of options in this space. 
[RDBMS](https://en.wikipedia.org/wiki/Relational_database)  [MySQL](https://www.mysql.com/) [SQL Lite](https://www.sqlite.org/index.html#:~:text=SQLite%20is%20a%20C%2Dlanguage,%2Dfeatured%2C%20SQL%20database%20engine.) [MSSQL](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) [Postgress](https://www.postgresql.org/)
[Non Relational](https://docs.oracle.com/middleware/1221/toplink/concepts/nosql.htm#OTLCG94411)  [Redis](https://redis.io/) [MongoDB](https://www.mongodb.com/) [Cosmos DB](https://azure.microsoft.com/en-us/products/cosmos-db)

Cosmos DB is a part of the Azure Cloud Services.  I do recommend you do a cloud based project [Azure](https://azure.microsoft.com/en-us/) [AWS](https://aws.amazon.com/free/?gclid=Cj0KCQiA-62tBhDSARIsAO7twbadWPTrEsdH8X_xlSLCcCCJkRfhEuXnEMgkQf7S_flpk2XZG3twq5oaAqt0EALw_wcB&all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=categories%23compute&trk=b53e5260-30f6-45cf-9610-30be63969231&sc_channel=ps&ef_id=Cj0KCQiA-62tBhDSARIsAO7twbadWPTrEsdH8X_xlSLCcCCJkRfhEuXnEMgkQf7S_flpk2XZG3twq5oaAqt0EALw_wcB:G:s&s_kwcid=AL!4422!3!610000101495!e!!g!!aws%20cloud!11086562321!108339554283) [Google Cloud Platform GCP](https://cloud.google.com/)) but part of the goal of this project is to learning, setting up, deploying and using all the technologies.

Data -> [IMBD Developers Site - Non-Commercial Datasets](https://developer.imdb.com/non-commercial-datasets/)  
Giant files that will need to be put into the data persistence service.  So that means learning how to get that data into persistence so it can be searched.

## Step Four - Use [Scrum](https://www.scrum.org/) and [Agile](https://en.wikipedia.org/wiki/Agile_software_development_) Principles
One of the pillars of the engineering world, is having a process that allows for organizing, documenting, tracking and delivering functionality amoung a team of developers.

For the last 15 or more years, that process has been Agile which is a more suited than other [software development processes](https://en.wikipedia.org/wiki/Software_development_process).

The quick summary is you have a Sprint (fixed amount of time, 2 weeks is a good amount) with a list of Stories (documented piece of work) that will be delivered (available to the users) at the end of the Sprint.

The software most used to manage the process is [JIRA](https://www.atlassian.com/software/jira)  I recommend you get a free account, read some tutorials and then use JIRA to organize the work in your project.

## Step Five - Document Your Work
Use your Knowledge Management tools for notes, JIRA to track the work of the project and GitHub to hold the various code/files. 

## Step Six - Complete Projects
One of the most important advice I can give you is focus on completing projects.  Part of being able to complete projects is keeping the scope reasonable.  Choose your Scope (what am I going to complete), Break that Scope Down (document those pieces into Stories), define a reasonable pace for your work (I am going to complete 3 stories a week).  This will give you a rough idea of when you will complete the work.

## Step Seven - Get Involved With [Open Source Projects](https://www.rocket.chat/blog/open-source-projects)
Open Source projects that are maintained by a community of developers.  Getting involved will help you learn how to contribute to software with a team of developers.
Also it is an excellent resume builder.  Part of submitting a change to an open source project is also getting reviewed by other developers which is a good experience to have.
Learning to discuss your code, describe your decision process, and interact with other developers is another important skill to develop

## Step Seven - Repeat
Keep learning, documenting and keep your focus on completing projects with demonstratable functionality.  

 





