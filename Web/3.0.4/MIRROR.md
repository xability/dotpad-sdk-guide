# Web SDK 3.0.4, served from this mirror

Dot Inc. publish Web SDK 3.0.4 in their repository only as an archive,
`Web/3.0.4/download/web-sdk-3.0.4.zip` at commit
`88583a619f10292b670943461aa4eec3cdda689e` of
https://github.com/dotincorp/dotpad-sdk-guide (SHA-256 of the archive:
`4f9095decdf831c5f1d7710a2bfda42a7a3701aab428d35454066d1ec96fb647`).
A CDN cannot serve a file from inside an archive, so this directory holds
that archive's contents, extracted verbatim: `DotPadSDK-3.0.4.js`,
`DotPadSDK-3.0.4.d.ts` and `lib/` with the braille engine
(`ttb-engine.mjs` and `.wasm`), the liblouis side module and tables, the
liblouis LGPL licence (`LIBLOUIS-COPYING.LESSER`), the MorphoBr notice and
the engine's build manifest. Every byte is the vendor's; `.gitattributes`
keeps git from normalising any of them.

MAIDR (https://github.com/xability/maidr) pins this directory by commit and
records each file's digest in `src/service/dotPadSdk.json`; its
`scripts/repin-dotpad-sdk.mjs` is what produced this directory and checks
it against the vendor's archive. Dot Inc. have given MAIDR permission to
redistribute the SDK.
