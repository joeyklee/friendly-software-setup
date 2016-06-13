# friendly-software-setup
This is a repository which tracks my software installation setup


# Setup docs:

## install web browsers

* firefox
* chrome

## install text editors

* sublimetext
* atom

## install xcode

## install homebrew

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## install python

```
brew install python
brew linkapps python
```
python 3

```
brew install python3
pip3 install jupyter
```

## install gdal
```
brew install node
```

## nodemon 
	npm install -g nodemon	
	

## mongodb
	brew install mongodb

## bower

```
npm install -g bower
```

### Download python packages

	pip install pandas scipy numpy matplotlib shapely fiona ipython
	
	
### Install R

	brew tap homebrew/science
	brew install r

## git

brew install git
	
## show hidden files

```
defaults write com.apple.finder AppleShowAllFiles YES
```

## install postgres
```
brew install postgres
brew install postgis

```

Test
```
 export PGDATA=/usr/local/var/postgres
 To quit psql, type the following command:

\q

When you have finished, don't forget to stop PostgreSQL:

pg_ctl stop

```

```
To have launchd start postgresql now and restart at login:
  brew services start postgresql
Or, if you don't want/need a background service you can just run:
  postgres -D /usr/local/var/postgres
  


PostGIS SQL scripts installed to:
  /usr/local/opt/postgis/share/postgis
PostGIS plugin libraries installed to:
  /usr/local/lib
PostGIS extension modules installed to:
  /usr/local/share/postgresql/extension
```
	
