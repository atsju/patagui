# Description
This is a Qt4/C++ client that allows to pick up songs from the patacrep songbook database to build personalized songbooks.

## Screenshots
![Client1](http://www.patacrep.com/images/stories/songbook-client1.png)
![Client2](http://www.patacrep.com/images/stories/songbook-client2.png)
![Client3](http://www.patacrep.com/images/stories/songbook-client3.png)

### Songbook
Since the songbook-client is only a viewer, you should retrieve songs first:
* required packages: python, texlive, texlive-lang-french
* git clone git://git.lohrun.net/songbook.git

#### Songbook-client
* required packages: cmake, liqt4-dev, libqt4-sql-sqlite
* build and run:
  git clone git://github.com/crep4ever/songbook-client.git
  cd songbook-client
  make && sudo make install
  songbook-client

##### Configuration
In the preferences, indicate the location of the patacrep songbook for example: ~/songbook

##### Contact & Forums
* www.patacrep.com
* crep@team-on-fire.com

