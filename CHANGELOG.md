Changelog for the gruf gem. This includes internal history before the gem was made.

h3. 0.11.2

- Ensure timer is measuring in milliseconds

h3. 0.11.1

- Fix issue with interceptor and call signature

h3. 0.11.0

- Add instrumentation layer and ability to register new instrumentors
- Add out-of-the-box statsd instrumentation support

h3. 0.10.0

- Rename Gruf::Endpoint to Gruf::Service
- Make services auto-mount to server upon declaration

h3. 0.9.2

- Support mount command on services to allow automatic setup on the server
- Cleanup and consolidate binstub to prevent need for custom binstub per-app

h3. 0.9.1

- Relax licensing to a clean BSD license

h3. 0.9.0

- Initial public release