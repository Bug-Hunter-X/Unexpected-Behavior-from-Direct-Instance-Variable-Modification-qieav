# Ruby Bug: Direct Instance Variable Modification
This example demonstrates a common yet subtle error in Ruby: directly modifying instance variables using `instance_variable_set` or `instance_variable_get`.  While functional, this approach undermines encapsulation and can lead to unpredictable results, particularly in larger or more complex projects.

The `bug.rb` file contains code that modifies an instance variable directly. The `bugSolution.rb` file shows the recommended alternative.