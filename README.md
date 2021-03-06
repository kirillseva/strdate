## strdate <a href="https://travis-ci.org/peterhurford/strdate"><img src="https://img.shields.io/travis/peterhurford/strdate.svg"></a> <a href="https://codecov.io/github/peterhurford/strdate"><img src="https://img.shields.io/codecov/c/github/peterhurford/strdate.svg"></a> <a href="https://github.com/peterhurford/strdate/tags"><img src="https://img.shields.io/github/tag/peterhurford/strdate.svg"></a>

**strdate** converts a text string into a date:

```R
> strdate::strdate("now")
[1] "2016-06-05 14:33:54 CDT"
> strdate::strdate("3 minutes from now")
[1] "2016-06-05 14:36:54 CDT"
> strdate::strdate("1 day from now")
[1] "2016-06-06 14:33:54 CDT"
> strdate::strdate("3 minutes ago")
[1] "2016-06-05 14:30:54 CDT"
> strdate::strdate("1 day and 3 minutes from now")
[1] "2016-06-06 14:36:54 CDT"
```

#### Acknowledgements

Code was taken from [Robert Krzyzanowski](https://github.com/robertzk)'s [testthatsomemore](https://github.com/robertzk/testthatsomemore) package, with permission.
