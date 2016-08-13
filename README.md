How to install Jupyter for Ruby?

Make sure your Ruby version is 2.1 or later
* rvm get stable
* rvm install ruby

Install Jupyter
* apt-get install python3-dev python3-pip python-virtualenv libzmq3-dev
* virtualenv -p python3 venv
* source venv/bin/activate
* pip install 'ipython[notebook]'

If you are using rvm, you can apply the .rvmrc in this repo.
Install bundler with "gem install bundler"
Then run "bundle"

Install Ruby gem
* gem install rbczmq
* gem install iruby

Launch Jupyter
* iruby notebook

For more information, go to https://github.com/SciRuby/iruby.
