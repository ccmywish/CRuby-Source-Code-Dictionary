# CRuby Source Code Dictionary

[![CRuby-Source-Code-Dictionary](https://github.com/ccmywish/CRuby-Source-Code-Dictionary/workflows/Test-Dict/badge.svg)](https://github.com/ccmywish/CRuby-Source-Code-Dictionary/actions/workflows/test.yml)

CRuby source code names explained using [cr: the Cryptic Resolver](https://github.com/cryptic-resolver/cr.rb). Please refer to its README to see the dictionary's layout and format.

<br>

My idea for knowledge management for C/C++ code base, is to record every abbreviation with its expansion. I'm glad to see that someone's effort is a very good example of [cr.rb](https://github.com/cryptic-resolver/cr.rb) target usage.

This repo is a transformation to cryptic resolver dictionaries from @tenderlove's https://github.com/tenderlove/ruby-glossary

## Usage

```bash
# Install cr command line tool
gem install cr.rb

# Add this dictionary
cr -a ccmywish/CRuby-Source-Code-Dictionary

# Update dictionaries
cr -u
```
