Forked from [benhoyt/benhoyt.github.com](https://github.com/benhoyt/benhoyt.github.com) to modify `_scripts/cloudfront_to_combined.py`, as follows:
- Add support for more data points to the user access logging (i.e, response status code, protocol version, and response byte count). 
- Add support for passing in a `--pixelPath` argument, which allows for the matching value of `cs-uri-stem` in the log record to be customized.

