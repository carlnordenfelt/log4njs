# 2.2.3
* Added zerofill to milliseconds

# 2.2.2
* Updated dev dependencies

# 2.2.1
* Updated dev dependencies

# 2.2.0
* Added `isDebugEnabled()`

# 2.1.0
* Introduced AUDIT & AUDIT_ALERT log levels.

# 2.0.0
##### Breaking changes
* New initialization:
    * `const log = require('log4njs)(options)`
* Removed functions:
    * options
    * setPrefix
    * setLogLevel
    * getSettings
* Removed log level:
    * fatal
    
##### Bug fixes
With the changes each logger instance is now self contained.
Configuration no longer spills over to other instances of the logger.

# 1.0.2
* Syntax fix

# 1.0.1
* Moved nyc to dev deps

# 1.0.0
* First release
