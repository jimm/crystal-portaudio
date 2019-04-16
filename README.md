# portaudio

Crystal bindings for the PortAudio library

**This is a WORK IN PROGRESS**

This fork by jim@jimmenard.com updates the code so that it compiles and runs
under newer versions of Crystal.

## Dependencies

* libportaudio:
 * On OSX: `brew install portaudio`
 * On Debian/Ubuntu: `apt-get install libportaudio`

## Installation

Add this to your application's `shard.yml`:

```yaml
dependencies:
  portaudio:
    github: jimm/portaudio
```

## Usage

```crystal
require "portaudio"
```

## Samples

    $> crystal samples/list.cr

## Contributing

1. Fork it ( https://github.com/jimm/crystal-portaudio/fork )
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create a new Pull Request

## Contributors

- [elthariel](https://github.com/elthariel) Julien 'Lta' BALLET - creator, maintainer
- [jimm](https://github.com/jimm) Jim Menard - updated for newer versions of Crystal
