# Welcome!

This is a test of the Github Pages deployment process.
It's been a struggle getting to this point, but finally I've done it!

## Some styling checks

First, I'm checking that [this link works.](./test.md)
I'm hoping that it does, since I have no idea how to implement it[^1].
I may also have to translate between the `.md` links I'm writing and the `.html` links I'm hoping will be generated.

[^1]: Like this hopefully!

It seems I will have to change this code:

```rust
let content = read_to_string(&p).ok()?;
let html = markdown_to_html(&content, &ComrakOptions::default());
```

1. The first element in a list
2. The second element in a list
3. The third

 * [ ] Hopefully this is a checkbox, don't know how this will be implemented.
 * [x] This should be checked off.

Those are all the tests I can think of right now, does MD have table support?

Firstly, $x=3$.
Next, as per the formula 
$ x + 1 = x - 1 + 2
  x + 1 = 3 - 1 + 2
    => x = 4
$