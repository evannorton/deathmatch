NOTES
=================

August 28, 2012
--------------
Viewed 52 Generations starting from scratch. 64 Organsims, 8 species.
Matches take too long. Reduce the match length to 500 or 600.
There is one killer species. It's fast moving snake of triangles, and it always either
KOs the opponent or bashes its own head in. Another species has adapted to a long imobile
snake. It either falls on or near the oppenent and does a little damage before being TKOed.
Presumably this species has no capacity for movement, so the extra damage points are enough
to drive it's evolution.

Most of the other species are similar to organisms found after the 5 generation. There is
very little variety. They do seem to have altered slightly. Most remain very ornate. A few
species never make it past the first round. I wonder if this is preventing them from 
receiving sufficient selection pressure to evolve (i.e. they are so far behind that small
improvements in fitness fail to have any benefit). Tools
to analyze a species over generations (phenotypically and genotipically) should be a high 
priority. 

Still no plan for speciation. Sibling species should be driven apart by competition over
resources. In this simulation, resources are organisms from other species. I would like to
see them alter which species they compete best against which should drive morphologic change.
Perhaps they can somehow be allocated breeding spots based on which species they do best
against. The way speciation is implemented is that dividing a species
will force it into matches with its former siblings. This will probably the largest source
of selection pressure. This will likely increse the diversity, but it will be difficult to
distinguish change driven by this new source of pressure from change driven by the new
genetic incompatibility.

Extinction is just as much a problem. Some species can always be expected to do 
miserably. If extinction is based on perfect failure, then we can expect species to go
extinct all the time. One posibility would to have a small probility of extinction at the end
of any generation where one of the species fails to win a single match. The gap could be
filled either by spliting an existing species (which might solve the speciation issue, but
reduce divesity) or generating a new random species (which would increase diversity but
muddle the concept of generational age).

TODO:

1. Some way of persisting simulation.
2. Reduce match length
3. Increase mutation rates.
4. Disqualify creatures with too many parts or that exceed certain bounds.
5. Info on current opponents.
6. Species analysis tools.
7. Tools to analyze competitiveness between species
8. KO bonus based on match length (shorter match = bigger bonus).