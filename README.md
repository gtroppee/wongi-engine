# Wongi::Engine

[![Join the chat at https://gitter.im/ulfurinn/wongi-engine](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ulfurinn/wongi-engine?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Build Status](https://travis-ci.org/ulfurinn/wongi-engine.svg?branch=master)](https://travis-ci.org/ulfurinn/wongi-engine) (MRI 1.9.3 to 2.3, Rubinius, JRuby)

[Feature annoucements](https://github.com/ulfurinn/wongi-engine/issues?q=is%3Aopen+is%3Aissue+label%3Aannoucement)

[Open discussions](https://github.com/ulfurinn/wongi-engine/issues?q=is%3Aopen+is%3Aissue+label%3Adiscussion)

[Tutorial](http://ulfurinn.github.io/wongi-engine/)

This library contains a rule engine written in Ruby. It's based on the [Rete algorithm](http://en.wikipedia.org/wiki/Rete_algorithm) and uses a DSL to express rules in a readable way.

**Word of caution**: this is complex and fragile machinery, and there may be subtle bugs that are only revealed with nontrivial usage. Be conservative with upgrades, test your rules extensively, and please report any behaviour that is not consistent with your expectations.

## Acknowledgements

The Rete implementation in this library largely follows the outline presented in [\[Doorenbos, 1995\]](http://reports-archive.adm.cs.cmu.edu/anon/1995/CMU-CS-95-113.pdf).

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
