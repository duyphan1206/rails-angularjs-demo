## Usage

### 1. Add the Gem

In Gemfile

```ruby
gem 'angular-rails-templates'
```

### 2. Include Templates in Rails Asset Pipeline

Then, in your `application.js` file, require `angular-rails-templates` and your templates:

```javascript
//= require angularjs
// ...
//= require angular-rails-templates
//
// Templates in app/assets/javascript/templates
//= require_tree ./templates
// OR
// Templates in app/assets/templates (but see step 5)
//= require_tree ../templates
```

Make sure to `require angular-rails-templates` **before** you require your templates.

source : https://www.angularonrails.com/