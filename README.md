Soundex.jl
==========

An implementation of the American Soundex algorithm in Julia as described by [Wikipedia](http://en.wikipedia.org/wiki/Soundex).

# Usage Examples

	using Soundex

	soundex("Robert") # => "R163"
	soundex("Rupert") # => "R163"
	soundex("Rubin") # => "R150"
