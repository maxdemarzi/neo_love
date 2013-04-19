neo_love
========

A POC Dating site with Neo4j

    git clone git://github.com/maxdemarzi/neo_love.git
    cd neo_love
    bundle install
    rake neo4j:install
    rake neo4j:create
    rackup
   
Open a browser to http://localhost:9292

On Heroku:

    git clone git://github.com/maxdemarzi/neo_love.git
    cd neo_love
    heroku apps:create neolove
    heroku addons:add neo4j
    git push heroku master
    heroku run rake neo4j:create

![ScreenShot](https://raw.github.com/maxdemarzi/neo_love/master/screenshot.png)