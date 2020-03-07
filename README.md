# bc extensions

Some collected functions and extensions for bc arbitrary precision
calculator.

These install to ~/bin/bc-extensions and can be used by creating an alias or not.
`alias bc="bc -l ~/bin/bc-extensions/*.bc"`

I've been using bc for years and the first thing I want is to change the scale.
I basically put my startup stuff in _~/bin/bc-extensions/_ then start bc 
with `bc -l ~/bc-extensions/*.bc`.
of course making that an alias for bc makes a lot of sense.
For more capabilities read the code.

# Installing

_make install_ should do the trick.
