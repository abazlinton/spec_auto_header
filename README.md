# spec_auto_header
Creates basic structure for Ruby spec files

### Usage:

- Copy `spec_auto_header.sublime-snippet` into `"~/Library/Application Support/Sublime Text 3/Packages/User/"`
- Type `!head` at the top of your _spec.rb file, then hit TAB


### Operation -
`a_very_long_file_name_spec.rb`

#### Becomes -
```
require 'minitest/autorun'
require 'minitest/rg'
require 'pry-byebug'
require '../a_very_long_file_name'

class TestAVeryLongFileName < Minitest::Test
	



end
```


