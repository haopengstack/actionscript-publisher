# EdgeCast Recorder

This is a Flash app that allows live-streaming to EdgeCast from a web browser.

This code is based on the work done by [Davide Bertola](http://dadeb.it/) in the [webproducer](https://github.com/davibe/webproducer) project.

## Notes

For ease of debugging, it uses the `flash.external.ExternalInterface` class do push all of its logging into JavaScript via console.log.


## TODO

- [] Detect if no camera is available and fail.
- [] Detect if no microphone is available and fail.
- [] Play more with camera resolution-detection in multiple browsers with different cameras.
