An example of the *Description Resource* containing the trusted actor list in Turtle format:

<!-- If deleting this comment, the code formatting will be errornous. -->

```turtle
@prefix : <urn:solid:mpc#>.

<https://uri/to/data>
  :trusted_actor_list
    <https://uri/to/trusted-actor-resrouce>.
```

An example of `https://uri/to/trusted-actor-resrouce` in Turtle format:

<!-- If deleting this comment, the code formatting will be errornous. -->

```turtle
@prefix : <urn:solid:mpc#>.

<>
  :trusted_actor
    <https://uri/to/actor1>,
    <https://uri/to/actor2>.
```