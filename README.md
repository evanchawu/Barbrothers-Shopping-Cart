# Note
It's a shopping cart system, let customers order merchandises, 
and checkout which is implemented by Braintree.

If you wanna to use Backend dashboard to increase products/category,
and see order lists, please go to rails console to edit role column of User from user to admin so that you have the Backend access authority.
<pre><code>
a = User.find_by(email:"your email")
a.update(role:'admin')
</code></pre>

After that click your account on the upper right corner, 
then you will found that "後台管理系統" bottom show up.

## How to run
* step1: git clone git@github.com:evanchawu/Barbrothers-Shopping-Cart.git
* step2: bundle
* step3: rake db:migrate
* step4: go to http://localhost:3000/

## Version
Rails 4.2.1

## GEMs
### Bootstrap
* gem 'bootstrap-sass'
* gem 'autoprefixer-rails'

### Form Processing
* gem 'simple_form'
* gem 'cocoon'

### File Upload
* gem 'carrierwave'

### Paging
* gem 'kaminari'
* gem 'bootstrap-kaminari-views'

### User
* gem 'devise'
* gem 'omniauth-facebook'
* gem 'cancancan'

### Debugging Tools
* gem 'hirb-unicode'
* gem 'better_errors'

### Testing Tools
* gem 'minitest-reporters'
* gem 'database_cleaner'
* gem 'capybara'
* gem 'guard'
* gem 'guard-minitest'

#### Fixture
* gem 'factory_girl_rails'
* gem 'faker'

