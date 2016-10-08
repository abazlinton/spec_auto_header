# spec_auto_header
Creates basic structure for Ruby spec files


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


