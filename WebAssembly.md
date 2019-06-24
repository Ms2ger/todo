- More tests
  * Immediately after a WebAssembly grow_memory instruction executes, perform the following steps:
  * Passing other kinds of BufferSource
- Get rid of the weird mathematics codepoints in the spec
- Periodically upstream jsapi tests into the Wasm spec repository
- Review browsers' repositories for upstreamable tests
- File bugs on non-SM engines after upstreaming into spec repo
- web-api tests
  * Should go into wpt only
  * Missing Content-Type header
- \[!!!] Re-review https://github.com/WebAssembly/spec/pull/873
- https://github.com/webpack/webpack/issues/8144 (delayed)
- https://github.com/WebAssembly/spec/pull/903: is test/harness/ still used?
- https://bugzilla.mozilla.org/show_bug.cgi?id=1519901 /  Move core wasm tests to jstests/wpt
- https://github.com/web-platform-tests/wpt/pull/15185
- https://github.com/WebAssembly/threads / wpt
- https://github.com/WebAssembly/threads/pull/118
- https://bugzilla.mozilla.org/show_bug.cgi?id=1515039 / slow jstests
- Write tests for https://github.com/WebAssembly/esm-integration/pull/21
- Review https://github.com/gsathya/proposal-weakrefs/pull/1 and https://github.com/guybedford/proposal-top-level-await/pull/1
- https://github.com/WebAssembly/multi-value/pull/8 / JS to wasm / @@iterator
- https://github.com/WebAssembly/host-bindings/pull/21
- https://github.com/heycam/webidl/issues/716
- https://github.com/WebAssembly/webidl-bindings/issues/27
- https://github.com/web-platform-tests/wpt/pull/16321
- https://github.com/WebAssembly/spec/issues/985
- https://github.com/web-platform-tests/wpt/pull/16313
- https://github.com/WebAssembly/spec/pull/745
- TLA
  * https://github.com/tc39/proposal-top-level-await/issues/63
    * update HTML
    * Upon settling, decrement the no-document.write counter
    * Synchronously, reset currentScript
  * Update Service Workers
  * Tests
- https://github.com/whatwg/html/issues/4601#issuecomment-491192671 / DetachArrayBuffer
- https://github.com/nodejs/ecmascript-modules/pull/46 / wasm modules
- Write test for load event: https://github.com/WebAssembly/spec/pull/745#issuecomment-493627056
