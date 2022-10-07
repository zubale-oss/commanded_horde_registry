
# CommandedHordeRegistry

  Process registration and distribution via [Horde](https://github.com/derekkraan/horde)

  In order to use this, you will need to update your commanded config

  ```elixir
  config :your_app, YourCommandedApp,
    registry: Commanded.Registration.HordeRegistry
  ```


## Installation

Add the following to your mix.exs deps:

```elixir
    {:commanded_horde_registry, github: "zubale-oss/commanded_horde_registry"}
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/commanded_horde_registry](https://hexdocs.pm/commanded_horde_registry).

