# Change Log

All notable changes to this project will be documented in this file starting from version **v1.1.0**.
This project adheres to [Semantic Versioning](http://semver.org/).

-----
## [1.7.3] - 2016-10-27
### Changed

- Updated dependencies.

### Fixed

- Fixed for docker-redis-cluster, https://github.com/thunks/thunk-redis/issues/19.

-----
## [1.7.2] - 2016-10-02
### Changed

- Updated dependencies.

-----
## [1.7.1] - 2016-09-14
### Changed

- Updated dependencies.

-----
## [1.7.0] - 2016-08-21
### Changed

- Updated engines to ">=0.12".

-----
## [1.6.7] - 2016-08-15
### Changed

- Updated dependencies.
- Improved socket send.

-----
## [1.6.6] - 2016-07-22
### Changed

- Updated dependencies.
- Added "TOUCH" command.

-----
## [1.6.5] - 2016-06-08
### Changed

- #18 support redis URL: redis://USER:PASS@redis.com:5678

-----
## [1.6.4] - 2016-06-07
### Changed

- Updated dependencies.

-----
## [1.6.3] - 2016-05-29
### Changed

- Improved performance.

-----
## [1.6.2] - 2016-05-24
### Fixed

- Fixed for PubSub keyword 'message'.

-----
## [1.6.1] - 2016-05-24
### Changed

- Removed "debug" module.
- Updated dependencies.

-----
## [1.6.0] - 2016-05-07
### Changed

- Supported redis v3.2.

-----
## [1.5.4] - 2016-03-16
### Changed

- Removed socket.cork account to a bug in node.js.

-----
## [1.5.3] - 2016-03-14
### Changed

- Updated dependencies.

-----
## [1.5.2] - 2016-03-01
### Changed

- Improve connection.

### Fixed

- Fixed for old redis(v2.8.x).

-----
## [1.5.1] - 2016-02-21
### Changed

- Updated dependencies.
- Improved code.

-----
## [1.5.0] - 2016-02-18
### Changed

- Removed auto-discover cluster nodes during initialization. Because the nodes information
from "cluster slots" command includes local-host information. But it will anto-connect
node by "MOVED" and "ASK".
- Changed files structure.

-----
## [1.4.1] - 2016-01-20
### Changed

- Updated dependencies.

-----
## [1.4.0] - 2015-12-29
### Changed

- Changed default `options.maxAttempts` to `5`.
- Added `options.onlyMaster`, it is useful for replication mode.
- Removed `options.handleError`.
- Supported IPv6.

-----
## [1.3.0] - 2015-12-13
### Changed

- Added `options.pingInterval`.
- Added `client.clientConnect`.

-----
## [1.2.4] - 2015-11-29
### Changed

- Updated dependencies.

-----
## [1.2.3] - 2015-11-27
### Fixed

- Fixed for slave node.

-----
## [1.2.2] - 2015-11-19
### Changed

- Updated description.

-----
## [1.2.1] - 2015-11-18
### Changed

- Improved performance.

-----
## [1.2.0] - 2015-11-12
### Changed

- Updated `thunks` to v4.0.0.

-----
## [1.1.1] - 2015-10-07
### Changed

- Added `clientReady` method.

### Fixed

- Fixed command `evalauto`.
- Fixed for `ASK`.

-----
## [1.1.0] - 2015-10-07
### Changed

- Added custom command `evalauto`.
- Used `const` instead of `var`.
