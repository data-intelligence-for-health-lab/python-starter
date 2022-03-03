# Python Starter

Use this repository as a base to start your python project.

It includes the basic best practices for writing clean and modular code.

To get a deeper understanding of the code structure and gain more background about this repository, feel free to view these lab [slides](https://docs.google.com/presentation/d/1g_gw_dwFGiW19xL7nRwJyib162vb0_HV_4HWr0Wnm2k/edit?usp=sharing).


## Structure

`/module` This folder shoul contain a single module. You can have multiple modules in this project. Feel free to rename it to whichever module name you like.

`/tests` This is where your tests will live.

`LICENSE` This file contains the license, by default its closed. To use an opensource license when the project is public, use the MIT License.

`.gitignore` Use this file to IGNORE any files that are sensitive and you don't want to commit to the repo (patient data, passwords and so on).

You can ignore induvidual files like `secrets.env`

You can ignore folders like `/data`

You can ignore nested files using GLOB patterns `/*/**/patients.csv` (This means, that inside any folder, as long as there is a file matching patients.csv, ignore it)

You can also ignore files based on their extensions `*.csv` or `/*/**/*.csv`

`requirements.txt` This is where your requirements for running this python project will reside (look at lab slides on instructions to generate this file)


## Questions?

Please feel free to open a pull request or reach out to me in the slack if you have any other questions that I haven't covered here.
