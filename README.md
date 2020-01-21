# Integration-capteurs-cellule-robotique

## Installation

Partir d'un projet Gazebo ariac et placez vous dans à la base du projet `cd ariac_ws`.

Sourcez le projet avec `source install/setup.bash`

Clonez ce package dans le dossier `src/tprobotique` avec `git clone https://github.com/OnlyShoky/Integration-capteurs-cellule-robotique.git src/tprobotique`

Installez avec `catkin_make install`

## Execution

Dans chacun des terminals utilisé, sourcez le projet avec `source install/setup.bash`

Lancez l'environement avec
`rosrun osrf_gear gear.py --development-mode -f src/tprobotique/data/planeta.yaml src/tprobotique/data/belt_objects_test1.yaml`

Executez notre package avec
`rosrun tprobotique main.py`

Démarez la simulation avec
`rosservice call /ariac/start_competition`
