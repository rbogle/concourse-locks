# concourse-locks

gate testing branch

- child is gate for child pipeline
- parent is gate for parent pipeline

parent sets and triggers child with child gate
child runs and sets gate in parent for autoclose
autoclose triggers parent to continue...
