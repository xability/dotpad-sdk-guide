# Web SDK 3.0.3, served from this mirror

Dot Inc. publish Web SDK 3.0.3 in their repository only as an archive,
`Web/3.0.3/download/web-sdk-3.0.3.zip` at commit
`781f2308b3b80908e7ea335454c12d013101c91b` of
https://github.com/dotincorp/dotpad-sdk-guide (SHA-256 of the archive:
`be0c0df63c5302bf6a374a80d3cc15197dc3032d93e1fc3c2cc9643d032dc3b8`).
A CDN cannot serve a file from inside an archive, so this directory holds
that archive's contents, extracted verbatim: `DotPadSDK-3.0.3.js`,
`DotPadSDK-3.0.3.d.ts` and `lib/` with the liblouis build, its LGPL-2.1
licence text and the wrapper sources the vendor asks redistributors to keep
beside it. Every byte is the vendor's; `.gitattributes` marks the binary
files so git leaves them alone.

MAIDR (https://github.com/xability/maidr) pins this directory by commit and
records each file's digest in `src/service/dotPadSdk.json`; its
`scripts/repin-dotpad-sdk.mjs` is what produced this directory and checks
it against the vendor's archive. Dot Inc. have given MAIDR permission to
redistribute the SDK.
