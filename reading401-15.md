# Trees

### Common Terminology
- Node: individual item/data that makes up the data structure
- Root: first/top Node (flexable with what is root)
- Left Child: node positioned to the left of a root or node
- Right Child: node positioned to the right of a root or node
- Edge: link between a parent and child node
- Leaf: node that does not contain any children
- Height: the number of edges from the root to the bottommost node

### Depth First
- Pre-order: root >> left >> right
- In-order: left >> root >> right
- Post-order: left >> right >> root
- Ex.
  - Pre-order: A, B, D, E, C, F
  - In-order: D, B, E, A, F, C
  - Post-order: D, E, B, F, C, A
     
          C
         / \
            F
        A   
            E
         \ /
          B
           \
            D
