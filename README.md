## Start Services
    docker-compose up

## after First Start: init DB
    docker-compose run manager python create_db.py

## update Submodules
    git submodule update --remote --recursive