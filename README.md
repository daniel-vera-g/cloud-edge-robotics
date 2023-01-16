# Cloud und Edge Robotics

[![Compile](https://github.com/daniel-vera-g/cloud-edge-robotics/actions/workflows/compile.yml/badge.svg)](https://github.com/daniel-vera-g/cloud-edge-robotics/actions/workflows/compile.yml)

> Paper on the Cloud and Edge Robotics

- Mainly covering ROS2(DDS) and Zenoh
- _Note:_ This paper and project is fully written in German

## Structure

_Directories:_

1. `./figures`: Images & co
2. `./sections`: Sections of the paper

_Files:_

1. `splncs04.bst`: Bibliography style 3
2. `literatur.bib`: Bibliography list
3. `llncs.cls`: Default formatting used in the document
4. `llncsdoc.sty`: Styles used in the Document
5. `Cloud-Edge-Robotics.tex`: Main content for the paper
6. `glossentries.tex`: Glossar
7. `Taskfile.yml`: Task runner. Requires `Task` dependency.

## Usage

1. `task`: Compile paper
2. `task open`: Compile and open pdf
3. `task clean`: Cleanup build files
