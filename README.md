# message_filter 

A size based or time based message filter. Takes any generic type as key and will dop keys after a time period or size of container is reached (Lru Cache pattern). The filter has Add key method only. Delete will be added at a later stage. This is a handy container for network based systems to filter previously seen messages.

Travis build and test status

[![Build Status](https://travis-ci.org/dirvine/message_filter.svg?branch=master)](https://travis-ci.org/dirvine/message_filter)


Appveyor build and test status (Windows)

[![Build status](https://ci.appveyor.com/api/projects/status/jsuo65sa631h0kav?svg=true)](https://ci.appveyor.com/project/dirvine/message_filter)

Code Coverage

[![Coverage Status](https://coveralls.io/repos/dirvine/message_filter/badge.svg)](https://coveralls.io/r/dirvine/message_filter)


[Documentation](http://dirvine.github.io/message_filter/)

#Todo
- [ ] Implement add_key  (bool return, true added, false == already exists)
- [ ] Test add_key (time and size based tests)
- [ ] API version 0.1.0
