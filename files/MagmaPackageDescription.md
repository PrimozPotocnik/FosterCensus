# Description of the magma package

This is a short description of the Magma code that imports the databases of all arc-transitive cubic graphs on up to 10000 vertices (Foster Census) and all cubic semisymmetric graphs on up to 10000 vertices.

## Cubic arc-transitive graphs

* ``load "ImportFosterCensus.mgm";``

  Requires also: FosterCensus10k.txt and FosterCensus10kplaces.txt

  Import the database of all cubic semisymmetric graphs on up to 10000 vertices into memory. The following magma function become available:

  * ``NumberOfCubicATgraphs(n);``

    Returns the number of cubic arc-transitive graphs on order $n$ vertice, for $n \le 10000$.

  * ``CubicATgraph(n,k);``

     Returns the k-th cubic arc-transitive graph on $n$ vertices.

## Cubic semisymmetric graphs

* ``load "ImportCubicSSCensus10k.mgm";``

  Requires also: CubicSScensus10kplaces.txt and CubicSScensus10k.txt

  Import the database of all cubic semisymmetric graphs on up to 10000 vertices into memory. The following magma function become available:

  * ``NumberOfCubicSSgraphs(n);``

    Returns the number of cubic semisymmetric graphs on order $n$ vertice, for $n \le 10000$.

  * ``CubicSSgraph(n,k);``

     Returns the k-th cubic semisymmetric graph on $n$ vertices.
