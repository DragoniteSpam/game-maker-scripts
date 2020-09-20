# GameMaker Scripts

A collection of general utility scripts for GameMaker Studio 2 (Version 2.3).

All scripts are included in the `scripts/` folder of this repository. Each script defines a single function. Most functions are standalone and are meant to be taken à la carte, but some of the more mathematically complicated functions depend on other scripts, indicated in a `@requires` tag. All function names begin with an underscore (`_`) in order to distinguish them from built-in functions.

The following is a brief description of the included functions, divided into rough categories.

## Array Functions

Common array functions (such as searching and counting).

* [`_array_count`](https://github.com/adam-rumpf/game-maker-scripts/blob/master/scripts/_array_count/_array_count.gml): Counts the number of occurrences of a specified value in an array.
* [`_array_index`](https://github.com/adam-rumpf/game-maker-scripts/blob/master/scripts/_array_index/_array_index.gml): Finds the first index at which a specified value occurs in an array (or -1 if not found). An optional argument allows the search to begin with a specified index.
* [`_array_max`](https://github.com/adam-rumpf/game-maker-scripts/blob/master/scripts/_array_max/_array_max.gml): Returns the maximum value in an array.
* [`_array_min`](https://github.com/adam-rumpf/game-maker-scripts/blob/master/scripts/_array_min/_array_min.gml): Returns the minimum value in an array.

## Computational Mathematics Functions

Algorithms from computational mathematics (such as regression and interpolation).

* `...`

## Linear Algebra Functions

Common linear algebra algorithms for dealing with matrices and vectors. In all functions, _vectors_ are considered to be 1D arrays while _matrices_ are 2D arrays.

* [`_matrix_multiply`](https://github.com/adam-rumpf/game-maker-scripts/blob/master/scripts/_matrix_multiply/_matrix_multiply.gml): Performs matrix-matrix, matrix-vector, and vector-vector multiplication.
* [`_matrix_transpose`](https://github.com/adam-rumpf/game-maker-scripts/blob/master/scripts/_matrix_transpose/_matrix_transpose.gml): Transposes a 2D matrix.
* [`_unit_vector`](https://github.com/adam-rumpf/game-maker-scripts/blob/master/scripts/_unit_vector/_unit_vector.gml): Defines a unit direction vector between two coordinates.
* [`_vector_angle`](https://github.com/adam-rumpf/game-maker-scripts/blob/master/scripts/_vector_angle/_vector_angle.gml): Calculates the acute angle between two vectors.
* [`_vector_distance`](https://github.com/adam-rumpf/game-maker-scripts/blob/master/scripts/_vector_distance/_vector_distance.gml): Calculates the Lp-distance between two vectors.
* [`_vector_norm`](https://github.com/adam-rumpf/game-maker-scripts/blob/master/scripts/_vector_norm/_vector_norm.gml): Calculates the Lp-norm of a vector.
* [`_vector_rotate`](https://github.com/adam-rumpf/game-maker-scripts/blob/master/scripts/_vector_rotate/_vector_rotate.gml): Rotates a 2D vector by a specified angle.
* [`_vector_scale`](https://github.com/adam-rumpf/game-maker-scripts/blob/master/scripts/_vector_scale/_vector_scale.gml): Scales a vector to maintain its direction while giving it a specified norm.

## Random Functions

Functions which involve randomization.

* [`_random_weighted_index`](https://github.com/adam-rumpf/game-maker-scripts/blob/master/scripts/_random_weighted_index/_random_weighted_index.gml): Chooses a random array index with probabilities defined by a given weight array.
* [`_random_sample`](https://github.com/adam-rumpf/game-maker-scripts/blob/master/scripts/_random_sample/_random_sample.gml): Draws a set of random samples from an array, either with or without replacement.
