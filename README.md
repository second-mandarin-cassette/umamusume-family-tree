# Uma Musume: Pretty Derby family tree
## Description
A cladogram visualizing the relations of the ingame characters and their real life ancestors.

## Raw data
The raw data is saved inside the file "umamusume_family_tree.csv".

## Generating the image
The SVG file is generated using the gnuclad tool. Its source code is found here https://launchpad.net/gnuclad or here at github https://github.com/FabioLolix/gnuclad.
The command to generate the SVG is:
`gnuclad umamusume_family_tree.csv umamusume_family_tree.svg umamusume_family_tree.conf`
