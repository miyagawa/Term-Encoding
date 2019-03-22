# NAME

Term::Encoding - Detect encoding of the current terminal

# SYNOPSIS

    use Term::Encoding qw(term_encoding);
    my $encoding = term_encoding;

    # ditto without exporting function
    use Term::Encoding;
    my $encoding = Term::Encoding::get_encoding();

# DESCRIPTION

Term::Encoding is a simple module to detect an encoding the current
terminal expects, in various ways.

# AUTHORS

Tatsuhiko Miyagawa <miyagawa@bulknews.net>

Audrey Tang <audreyt@audreyt.org>

# COPYRIGHT

Copyright 2019 Tatsuhiko Miyagawa

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO

[Locale::Maketext::Lexicon](https://metacpan.org/pod/Locale::Maketext::Lexicon)
