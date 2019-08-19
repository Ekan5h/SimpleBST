# SimpleBST
This is a simple Binary Search Tree implementation in C++ using classes and templates.
A binary search tree is a data structure which stores data as nodes linked together meaningfully. Each node has a left node, a right node and a parent node. The parent node can be skipped while coding recursively. Conventionally, the "meaning" is specified as, the left node is always smaller than the current node while the right node is always greater. So a typical BST looks something like this:
                                                          
                                                         (root)
                                                          /  \
                                                        /      \
                                                      /          \
                                                    /              \
                                                (l)                   (r)
                                               /   \                 /   \
                                             /       \             /       \
                                         (ll)        (lr)       (rl)        (rr)
                                         / \         / \        / \         / \
                                     (lll) (llr) (lrl) (lrr) (rll) (rlr) (rrl) (rrr)
                                             
The first node is called the root node as the tree starts growing from that node. In the above representation each node is named as the path you would have to take to arrive at that node from the root. Thus, in a fully balanced tree as shown above, searching in a tree with 15 nodes would take at most 3 steps to reach any node. 
