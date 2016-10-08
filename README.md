# spec_auto_header
Creates basic structure for Ruby spec files

###Usage:

Copy 
Type "!head" at the top of your <class_name>_spec.rb file


`a_very_long_file_name_spec.rb`

Becomes -
```
require 'minitest/autorun'
require 'minitest/rg'
require 'pry-byebug'
require '../a_very_long_file_name'

class TestAVeryLongFileName < Minitest::Test
	



end
```


