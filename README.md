# Tree

Raku implementation of variants of the Binary Tree, e.g., BST, AVL, Red-Black, and M-Ary

## Synopsis
    use Tree::AVL; # default: unique keys, i.e., a set
    
    my $tree = Tree::AVL.new;
    $tree.insert: 1, :data<some text>;
    # check for success
    say $tree.result; # output: True
    $tree.insert: 1;
    say $tree.result; # output: False
    ...
    
## Implementation status
1. BST - Work in progress (WIP)
2. AVL - WIP
3. Red-Black - Planned
4. M-Ary - Planned

## References
1. Introduction to Algorithms, Third Edition; by ...

## Copyright
Copyright (c) 2009, Thomas Browder <tom.browder@gmail.com>

## LICENSE
Artistic-2.0

