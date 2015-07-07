## Harp + Bootstrap (SCSS)

#### Background
We use Bootstrap at my work (http://thezebra.com) and I wanted to work on my SCSS and Bootstrap skillz. I played around a little with the boostrap sass gem that comes with compass but couldn't access all the Bootstrap files to fully cuztomize my Bootstrap build. I've spent some time working with Harp recently and decided that it would be a good solution. The existing blogs / repos I found weren't super eassy to get working straight out of the box. So I basically just copied all the Bootstrap files from their scss build and wired them up to work with a Harp site.

#### Setup

###### Start by downloading node from their official site if you have yet. This is super easy through their installer thing.

nodejs.org

###### Install npm to help install Harp and other packages.

```
node install npm
```

###### Install harp through npm

```
npm install -g harp
```

###### Clone this repository in the directory you want to work on.

```
cd to/directory/you/want/to/work/from
git clone https://github.com/mattjared/harp-bootstrap-scss.git
``

###### Start your harp server

```
harp server
```

From here you'll fire up localhost:9000 and have acccess to a Harp site that uses Bootstrap. You can access the Bootstrap SCSS files and start playing around. Enjoy!

##### Please note

This project isn't affiliated with Bootstrap or Harp. I just copied the Bootstrap files and piped them into the main.css file with Harp so it'll be easier for the next person to get up and running. If this violates any terms or anything please let me know and I'll edit / delete as needed. Submit pr's / complaints / whatver as needed. Thanks!