## Powered by Rails 3.0.9 and [Dalli](https://github.com/mperham/dalli)

Provides a simple demonstration of action caching with memcached using the dalli gem.
The demo contains two models, User has many Widgets which belong to user (0..N relationship).

This also has the benefit of demonstrating a simple nested route for those new to rails.
Widgets can only be accessed via users. The user show method is being cached which also displays widget data.

### cheers

