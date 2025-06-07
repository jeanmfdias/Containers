#!/bin/bash

echo "Run project containers"

param1=$1
param2=$2

if [ "$param1" = "--mysql" -a "$param2" = "5.7" ] 
then
    cd ./mysql
    docker compose up -d
    echo "MySQL 5.7 Running"
elif [ "$param1" = "--mysql" -a "$param2" = "8" ]
then
    cd ./mysql8
    docker compose up -d
    echo "MySQL 8 Running"
elif [ "$param1" = "--postgres" ]
then
    cd ./postgresql
    if [ "$param2" = "stop" ]
    then
        docker compose down
        echo "PostgreSQL Stopped"
    else
        docker compose up -d
        echo "PostgreSQL Running"
    fi
    cd ..
elif [ "$param1" = "--redis" ]
then
    cd ./redis
    if [ "$param2" = "stop" ]
    then
        docker compose down
        echo "Redis Stopped"
    else
        docker compose up -d
        echo "Redis Running"
    fi
    cd ..
else
    echo "No container specified"
fi
