# spec_auto_header
Creates basic structure for Ruby spec files

### Usage:

- Copy `spec_auto_header.sublime-snippet` into 

`"~/Library/Application Support/Sublime Text 3/Packages/User/"`
- Type `!head` at the top of a spec file, then hit TAB

### Result:
```
require 'minitest/autorun'
require 'minitest/rg'
require 'pry-byebug'
require '../a_very_long_file_name'

class TestAVeryLongFileName < Minitest::Test
	



end
```
### Limitations:

- Will only work with spec files named `exactly_like_this_spec.rb` and with a Class file named `exactly_like_this.rb` in the directory above.

