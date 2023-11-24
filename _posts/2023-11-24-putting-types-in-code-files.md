---
layout: post
---

I think we should define our types in the code files that use them.
For example, instead of this

```python
# foo.py

def foo(arg1)
```

do this

```python
# foo.py

class type1:
    """
    Needs to be able to do the following

    - thing1
    - ...
    """

def foo(arg1: type1)
```

And then all users know exactly what type of argument
to pass in. 

Also, the beauty of this is that all of your files are
able to be broken off and treated individually as
their own little packages.

The contrast would be if you had the
type definition in a different file, and in the
function file, you'd import the type. But this
is what we want to avoid. We want the types
to be defined in the same file because then
the code is more modular and can be treated as their
own little packages.

And I think this actually might be a little bit of what
object oriented programming was intended to be, but
we may have missed the mark
