# Web SDK 3.0.5, served from this mirror

Dot Inc. publish Web SDK 3.0.5 in their repository only as an archive,
`Web/3.0.5/download/web-sdk-3.0.5.zip` at commit
`d1394f0df6609e1b79ad3635f4e66e68f4368c72` of
https://github.com/dotincorp/dotpad-sdk-guide (SHA-256 of the archive:
`224460375c64b928d5bfdb26de83fa6015a36de3ad343780f02b4116501b3096`).
A CDN cannot serve a file from inside an archive, so this directory holds
that archive's contents, extracted verbatim: `DotPadSDK-3.0.5.js`,
`DotPadSDK-3.0.5.d.ts` and `lib/` with the braille engine
(`ttb-engine.mjs` and `.wasm`), the liblouis side module and tables, the
liblouis LGPL licence (`LIBLOUIS-COPYING.LESSER`), the MorphoBr notice and
the engine's build manifest. Every byte is the vendor's; `.gitattributes`
keeps git from normalising any of them.

MAIDR (https://github.com/xability/maidr) pins this directory by commit and
records each file's digest in `src/service/dotPadSdk.json`; its
`scripts/repin-dotpad-sdk.mjs` is what produced this directory and checks
it against the vendor's archive. Dot Inc. have given MAIDR permission to
redistribute the SDK.
