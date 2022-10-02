Reflection components allowing to inline new types/behaviors.

## Component
Type which will take delegates for its own calls.
```rust
use framework::specializations::Graph;

let dec = Declaration::of( Component::with([
  Declaration::Apply(| context |{}),
  Graph::Children(| context | { todo!() })
  ]) );
```

## Declaration 
