# Integration-capteurs-cellule-robotique

# Installation

Partir d'un projet Gazebo ariac et placez vous dans à la base du projet `cd ariac_ws`.

Sourcez le projet avec `source install/setup.bash`

Clonez ce package dans le dossier `src/tprobotique` avec `git clone https://github.com/OnlyShoky/Integration-capteurs-cellule-robotique.git src/tprobotique`

Installez avec `catkin_make install`

# Execution

Dans chacun des derminal utilisé, sourcez le projet avec `source install/setup.bash`

Lancer l'environement 
`rosrun osrf_gear gear.py --development-mode -f src/tprobotique/data/planeta.yaml`

Pour executer notre package
`rosrun tprobotique main.py`

Pour démarer la simulation
`rosservice call /ariac/start_competition`
