# finnest-static

Public mirror of Finnest CLI release assets — platform binaries, runtime
tarballs, their cosign Sigstore bundles, `install.sh`, `finnest.rb`, and
`SHA256SUMS` — for the private `finnestbr/finnest-power` repository.

Releases here are produced automatically by the finnest-power publish pipeline
(the `static-mirror` distribution stage) and verified with cosign keyless
(bundle-only) against the `finnestbr/finnest-power` release workflow identity.
