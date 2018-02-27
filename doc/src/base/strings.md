# [Strings](@id lib-strings)

```@docs
Base.length(::AbstractString)
Base.sizeof(::AbstractString)
Base.:*(::Union{Char, AbstractString}, ::Union{Char, AbstractString}...)
Base.:^(::AbstractString, ::Integer)
Base.string
Base.repeat(::AbstractString, ::Integer)
Base.repeat(::Char, ::Integer)
Base.repr(::Any)
Core.String(::AbstractString)
Base.SubString
Base.transcode
Base.unsafe_string
Base.ncodeunits(::AbstractString)
Base.codeunit
Base.codeunits
Base.ascii
Base.@r_str
Base.@raw_str
Base.Docs.@html_str
Base.Docs.@text_str
Base.isvalid(::Any)
Base.isvalid(::Any, ::Any)
Base.isvalid(::AbstractString, ::Integer)
Base.match
Base.eachmatch
Base.isless(::AbstractString, ::AbstractString)
Base.:(==)(::AbstractString, ::AbstractString)
Base.cmp(::AbstractString, ::AbstractString)
Base.lpad
Base.rpad
Base.findfirst(::AbstractString, ::AbstractString)
Base.findnext(::AbstractString, ::AbstractString, ::Integer)
Base.findlast(::AbstractString, ::AbstractString)
Base.findprev(::AbstractString, ::AbstractString, ::Integer)
Base.contains
Base.reverse(::Union{String,SubString{String}})
Base.replace(s::AbstractString, ::Pair)
Base.split
Base.rsplit
Base.strip
Base.lstrip
Base.rstrip
Base.startswith
Base.endswith
Base.first(::AbstractString, ::Integer)
Base.last(::AbstractString, ::Integer)
Base.uppercase
Base.lowercase
Base.titlecase
Base.ucfirst
Base.lcfirst
Base.join
Base.chop
Base.chomp
Base.thisind
Base.nextind
Base.prevind
Base.textwidth
Base.isalpha
Base.isascii
Base.iscntrl
Base.isdigit
Base.islower
Base.isnumeric
Base.isprint
Base.ispunct
Base.isspace
Base.isupper
Base.isxdigit
Core.Symbol
Base.escape_string
Base.unescape_string
```