# species
- An open learning project about species in nature - 

The idea of Species came to my mind when reading about how many species get extincted every day(!) and were never known to probably 98% of the world's population. So it's about knowledge and responsibility. Becoming responsible for one species and to protect it from extinction gives each individual human a closer band to protecting the environment. Instead of staying stale and in awe of the sheer size of climate change and environment protection, a human individual gets a defined target to get knowledgeable about his/her species, its behavior, its history in evolution, its needs, its dependencies. 

The platform should work as follows:

1. A user gets a page with a button, upon clicking she will be provided with a species' scientific name, and if available, a picture. 
2. The user clicks the button again to switch to a different species, or presses a further button to accept the species
3. After accepting, the user will be provided with more details on the species
4. The user is asked to register, in order to take care of the species. 
5. Registration is limited to e-mail address and a password, and if she is a specie's expert / a double opt-in e-mail message is sent to confirm the validity of the e-mail address
	- species experts are asked in the e-mail message to provide proof of their expertise (tbd)
	- each user gets a logo with an abstract version of the species 
6. Once registered, the user will be provided with a dashboard: 
	- on the top right corner, the name and a picture of the species is displayed
	- below on the right, a short fact sheet of the species is displayed
	- on the left (main area), a notebook is offered to put in notes about the species, which were found while looking for information. (Could be single bubbles, which hold pictures, links, videos, text information / tbd). This information needs to be tagged for what kind of information is given in each bubble
	- bubbles can be rearranged and can form a parent/child relationship, or a partner relationship
7. Once the user has added 10 bubbles with information, she can share information which she deems outstanding or very helpful for others with the public
8. On a different (public) dashboard, these shared info bubbles are shown, and can be voted upon how helpful they are. A user can only vote once per bubble. 
9. A species expert will be able to validate the shared information and highlight as particularly correct or not
10. On the public dashboard, people will be able to discuss bubbles (discussion text appears below a bubble)
11. Users will get points for votes on bubbles and will receive badges depending on the amount of points as eg egg, larve, grub, junior, pa, king/queen, species, species expert to show the expertise she acquired while occupying herself with the species 
12. Once one user reached the species expert status, she won't be able to share more data on this species, but to help novices to find out about a species. 
13. It is to be questioned whether the gathering for knowledge should be round-based, i.e. once one user acquires the 'species expert' status, the round is done, all species members get informed with this and will be asked if they want to start over with a different species or if they want to continue with the same species.

### Data ###
1. The Catalogue of Life (http://www.catalogueoflife.org/) shall be used for species' suggestions and for fact sheets
2. User password will be salted and encrypted (bcrypt)
3. matomo will be used for tracking (server side only / no google tag manager whatsoever, only anonymous tracking)

### Platform security ###
The platform shall be secured by websec best practices.

### Hosting ###
The platform shall be hosted on a provider which runs on green energy

### Open data platform ### 
The platform will be non-commercial, worldwide access shall be possible. All data provided by the users shall be open and free to be reused for other purposes. 

### Your involvement ###
I'm looking for people for further discussing the requirements for this platform and need help to put it into code, as I know many things, but too little about programming in current frameworks. 
Whether it shall be a native or PWA app or just a plain web application is tbd.

### Example ###
Take some minutes of your time to find out about "Actinotrocha californica Temereva"
