[![Actions Status](https://github.com/akiym/JSON-Hjson/actions/workflows/test.yml/badge.svg)](https://github.com/akiym/JSON-Hjson/actions)

NAME
====

JSON::Hjson - Human JSON (Hjson) deserializer

SYNOPSIS
========

    use JSON::Hjson;

    my $text = q:to'...';
    {
      // specify delay in
      // seconds
      delay: 1
      message: wake up!
    }
    ...
    say from-hjson($text).raku;

DESCRIPTION
===========

JSON::Hjson implements Human JSON (Hjson) in Raku grammar.

SEE ALSO
========

[JSON::Tiny](JSON::Tiny)

[https://hjson.github.io/](https://hjson.github.io/)

AUTHOR
======

Takumi Akiyama <t.akiym@gmail.com>

COPYRIGHT AND LICENSE
=====================

Copyright 2016 Takumi Akiyama

This library is free software; you can redistribute it and/or modify it under the Artistic License 2.0.

