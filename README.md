# Library JpGraph loader for composer

## Version 4.2.0
* Compatible PHP 7.1

## Installation

edit : composer.json

    {
        "repositories": [
            [...],
            {
                "type": "git",
                "url": "https://github.com/steelice/JpGraph.git"
            }
        ],
        "require": {
            [...]
            "steelice/JpGraph" : "4.2"
        }
    }

JpGraph from http://jpgraph.net/
======
This is a port for Composer users to use JpGraph as a Vendor library

use JpGraph\JpGraph::load(); and JpGraph\JpGraph::module('moduleName'); to load required modules
