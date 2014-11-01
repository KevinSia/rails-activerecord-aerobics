# Rails ActiveRecord Aerobics
Boost your [Rails ActiveRecord Query](http://guides.rubyonrails.org/active_record_querying.html) core fitness with this workout plan. For the home, office, and gym.

Rails ActiveRecord Aerobics is a collection of exercises to help you learn, practice, and master Rails ActiveRecord Querying. 

This is for all Rails developers of all experience levels. 

The exercises build on each other to strengthen your query skills bit-by-bit. Take them as fast or as slow as you like.

## Draft Workout Plans (work in progress)

### What to practice?

From `find` to advanced queries using `join`, `includes`. Everything covered in Rails ActiveRecord Querying guide and anything else useful not mentioned. Comb through API docs. 

Don't be too abstract with models, favour classes developers might encounter in a day job.

### What's the easiest flow for newcomers?

1. `git clone` (skip fork?)
2. `cd rails-activerecord-aerobics`
3. `bundle install`
4. `rake gen` to generate workout plans/spec skeletons (see Ruby Koans). Templates (and solutions?) live in `./plans`. Specs to be edited will be generated in `./spec`
5. `rspec` or `rake go` to begin working out/running specs in `./spec`
6. Rely on rspec expectations to provide coaching

### How to structure the specs?

First x specs each deal with one topic and a set of tightly related drills using a mix of model families:

1. a01_find_spec
2. a02_find_by_spec
3. a03_find_by_*_spec
4. a04_where_spec
5. ???
9. a09_joins_spec
10. a10_basic_sql_spec
11. a11_advanced_sql_spec

Last y specs focus on one family of models each, with exercises that make use of all previously learned skills. Start off with a few finds, then some find_bys, and work up to joins and more, all in one spec file for each model family.

1. b01_book_spec
2. b02_invoice_spec
3. b03_credit_card_spec
4. b04_customer_spec
5. b05_product_spec
6. b06_content_spec
7. b07_user_spec
8. b08_money/account/finance_spec
9. ???

