# Inheritance

My solution to the [Inheritance](https://cs50.harvard.edu/x/psets/5/inheritance/) problem set from [CS50x](https://cs50.harvard.edu/x/).

## Description

Each person has two alleles (A, B, or O) that determine their blood type. A child inherits one allele randomly from each parent. This program:

1. Recursively creates a family tree of 3 generations
2. Assigns random alleles to the oldest generation (grandparents)
3. Passes down alleles from parents to children
4. Prints the family tree with each member's blood type
5. Frees all dynamically allocated memory

## Usage

```
$ make inheritance
$ ./inheritance
```

### Example Output

```
Child (Generation 0): blood type OA
    Parent (Generation 1): blood type AO
        Grandparent (Generation 2): blood type OA
        Grandparent (Generation 2): blood type BO
    Parent (Generation 1): blood type OB
        Grandparent (Generation 2): blood type AO
        Grandparent (Generation 2): blood type BO
```
