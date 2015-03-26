# sentry-install-guide
A quick guide to installing Sentry on Ubuntu 14.04.1

```sh
    apt-get install git elinks virtualenv python-dev python-pip python2.7-dev npm
    apt-get install libpq-dev postgresql-server-dev-9.3 libxslt1-dev libxml2-dev libz-dev libffi-dev libssl-dev
    sudo ln -s /usr/bin/nodejs /usr/bin/node
    
    
    pip install -U virtualenv
    virtualenv /www/sentry/
    
    source /www/sentry/bin/activate
    cd /www/sentry
    
    git clone git@github.com:getsentry/sentry.git
    
    cd sentry
    
    npm install
    npm install bower
    npm isntall gulp-less
    pip install -U sentry
    pip install -U sentry[postgres]
```

## Todo
* Finish getting postgres user & table created
