chess
=====

attempt at a multithreaded c++ chess program
main features
extensive use of STL.
Ply generation is done concurrently for the separate pieces, using a producer-consumer paradigm
memory footprint kept low by storing data only for pieces that are really there.
Also, there is only one square offboard.
