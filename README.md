# Uma Musume: Pretty Derby family tree
## Description
A cladogram visualizing the relations of the ingame characters and their real life ancestors. It can be viewed here: https://second-mandarin-cassette.github.io/umamusume-family-tree/

## Working with the data set

### Modifying the data set
The raw data is saved inside the file "umamusume_family_tree.csv".

### Generating the image
The SVG file is generated using the gnuclad tool. Its source code is found here https://launchpad.net/gnuclad or here at github https://github.com/FabioLolix/gnuclad.
The command to generate the SVG is:

`gnuclad umamusume_family_tree.csv umamusume_family_tree.svg umamusume_family_tree.conf`

### Sorting the entries
The gnuclad tool can sort the csv file by "start date". A different configuration file is used then. The tool the produces a new csv file. Invocation:

`gnuclad umamusume_family_tree.csv umamusume_family_tree_sorted.csv sort.conf

## TODO
- [ ] Use different colors for vertical connections

## Thanks
Thanks goes to the project https://github.com/eylenburg/os-family-tree which was taken as inspiration.
