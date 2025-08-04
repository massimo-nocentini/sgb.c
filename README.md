# The Stanford GraphBase

A mirror of [The Stanford GraphBase: A Platform for Combinatorial Computing](https://www-cs-faculty.stanford.edu/~knuth/sgb.html), 
we just provide a small change in the Makefile so that the compiled library can be linked (actually, we just add the `-fPIC` flag). 
Moreover, we compile some PDF files about core components.

## Compilation

In order to compile and install, we provide a new `Makefile` rule `complete`; please do:

```bash
cd src && make complete
```

provided that both `clang` and `texlive` are available in your system.

## PDF files

Some additional documentation extracted and compiled from `.w` core sources:

|PDF|Summary|
|---|---|
|[gb_graph.pdf](./src/gb_graph.pdf)|Data structures for graphs|
|[gb_flip.pdf](./src/gb_flip.pdf)|System-independent random number generator|
|[gb_io.pdf](./src/gb_io.pdf)|Input/output routines|
|[gb_sort.pdf](./src/gb_sort.pdf)|Sorting routine for linked lists|
|[gb_basic.pdf](./src/gb_basic.pdf)|Standard building blocks and graph operations|
|[gb_books.pdf](./src/gb_books.pdf)|Graphs based on world literature|
|[gb_econ.pdf](./src/gb_econ.pdf)|Graphs based on US inter-industry flow|
|[gb_games.pdf](./src/gb_games.pdf)|Graphs based on college football games|
|[gb_gates.pdf](./src/gb_gates.pdf)|Graphs based on combinational logic|
|[gb_lisa.pdf](./src/gb_lisa.pdf)|Graphs based on Leonardo's Mona Lisa|
|[gb_miles.pdf](./src/gb_miles.pdf)|Graphs based on highway distances|
|[gb_plane.pdf](./src/gb_plane.pdf)|Planar graphs|
|[gb_raman.pdf](./src/gb_raman.pdf)|Ramanujan graphs (expanders)|
|[gb_rand.pdf](./src/gb_rand.pdf)|Random graphs|
|[gb_roget.pdf](./src/gb_roget.pdf)|Graphs based on Roget's Thesaurus|
|[gb_words.pdf](./src/gb_words.pdf)|Graphs based on 5-letter words of English|
|[assign_lisa.pdf](./src/assign_lisa.pdf)|The assignment problem, using Mona Lisa|
|[book_components.pdf](./src/book_components.pdf)|Biconnected components, using the plots of books|
|[econ_order.pdf](./src/econ_order.pdf)|Heuristic solution to an optimum permutation problem|
|[football.pdf](./src/football.pdf)|Heuristic solution to a longest-path problem|
|[girth.pdf](./src/girth.pdf)|Empirical study of Ramanujan graphs|
|[ladders.pdf](./src/ladders.pdf)|Shortest paths in word graphs|
|[miles_span.pdf](./src/miles_span.pdf)|Comparison of algorithms for minimum spanning tree|
|[multiply.pdf](./src/multiply.pdf)|Using a parallel multiplication circuit|
|[queen.pdf](./src/queen.pdf)|Graphs based on queen moves|
|[roget_components.pdf](./src/roget_components.pdf)|Strong components of a directed graph|
|[take_risc.pdf](./src/take_risc.pdf)|Using a simple RISC computer circuit|
|[word_components.pdf](./src/word_components.pdf)|Connected components of word graphs|