## 2.4.0

* Updated Capybara

## 2.3.0

* Adds `Capybara::Node::Email#header` and `Capybara::Node::Email#headers` for retrieving optional headers set on an email.
* Corrects `inspect` of `Capybara::Node::Email` 
* Delegate all missing methods in `Capybara::Node::Email` to `base.email`
