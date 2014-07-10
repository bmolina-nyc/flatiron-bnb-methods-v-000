---
tags: rails, full application, class methods, instance methods, validations
language: ruby
unit: rails
module: Building Complete Apps
level: advanced
resources: 0
---

# Flatiron-bnb: Methods

In the previous iteration, we built out our model associations and migrated our database. Now we're going to work on building useful methods (class and instance) for rendering data and our own validations. We're doing this to follow the principle that our controllers should be skinny, our models fat, so therefore our views have very little logic in them.

<em>Before anything</em>, note that when you generate models, controllers, etc, be sure to include this option, so that it skips tests (which we already have): `--no-test-framework`

## Methods

validations maybe? (make these instance methods)
- owners cannot rent own apartments
- renters cannot rent two apartments at the same time
- a listing cannot be booked by two renters at the same time


## Resources

