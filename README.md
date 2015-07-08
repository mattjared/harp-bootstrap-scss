## Harp + Bootstrap (SCSS)

#### Background
We use a custom Bootstrap SCSS build at [my work](http://thezebra.com) and I wanted to tune up my skills but found it hard to just open up the Bootstrap SCSS files and get going on a new sandbox site. The [Bootstrap Sass](https://github.com/twbs/bootstrap-sass) docs show how to get up and runnng with Compass or a Rails. If you want to use either of those or have a project similar to that setup, you should totally go there and work through their docs. Another option is to use Less with the already existing package [Harp Bootstrap](http://jvandemo.github.io/hb-bootstrap/docs/). An even better option would be to use the existing [Bootstrap Sass project](https://github.com/harp/bootstrap-sass) that gets you all that beautiful code. None of these solutions worked for my needs though. I couldn't just download or clone something and turn it on. That's what this repo is. All I did was pipe in the Bootstrap SCSS files into an existing Harp site.

#### Setup

If you haven't donwloaded node, we'll need that and one other thing to get going. Downloading node is super easy through their installer at [nodejs.org](http://nodejs.org). Node comes with [npm](http://npmjs.org) which we will use to install Harp.

After you've install node (and npm)
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