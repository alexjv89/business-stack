# Introduction


This is a collection of components(software tools, libraries, external saas service), that you can put together to improve the efficiency of your business processes. 


This business software stack is best suited for businesses that already has some operations running and wishes to use software for optimizing operations or automating some parts. 


I have been using this stack for over 3 years with multiple of my personal side projects and at places I consult. I have been "rinse and repeating" this stack so often that its probably worth writing down.

Some of my personal projects that uses this stack:
- www.cashflowy.in
- www.massivetimesaver.com
- www.highlyreco.com

As developers we are spoiled with choice. Sometimes choice can be a b=

## Disclaimer

I dont claim that this stack is the best stack in the world. The best stack is the one that you are most familiar with. If you are already familiar with php and heroku, that is probably the best stack for you. 


## Stack design choice
This stack was designed with couple of constaints in mind. 

There were 2 major constraints:
#### Constraint 1: It should work for a one man shop
#### Constraint 2: It should be sort of scalable, in case scale was required


## Business stack
- Javascript (programming language)
- AWS (Platform as service)
- Elastic Search via AWS (for log processing)
- S3 (for static website, for storing and service files)
- Semantic-ui (css framework)
- Postgres via RDS AWS (for datastore)
- Sailsjs (Web development framework)
- Slack (Communication / Alerts)
- Uptime robot (Monitoring system)
- Setcronjob (Run cron jobs remotely)
- Gitlab (code versioning and automated testing)
- Gitlab runner (for automated testing)
- Google analytics 
- Redis -  via Elastic Cache - AWS (for session store)
- Cloudflare (dns mapping, ddos protection)
- Sentry (error logging)
- Logstash (piping logs to elastic search)
- Algolia (search as a service)
- Kue (queing library)
- Hotjar (understand how users are behaving on your website)

## Who is this stack best suited for? 
- Someone who wants to learn enough tech to be able to bring your ideas to life
- Someone who wants to build a small high performance team of full stack developers within your organization, building out business integrations and automations (this is what I do as a consultant)


## Who is this stack not for?
- this might not work for large companies which has specific performance problems to tackle. I am not saying this stack will not work in high scale production environment. It will. But depending on what you are trying to opimize for some other stack might be best suited for you. 
- someone who is super proficient in RoR. If you are already good at RoR