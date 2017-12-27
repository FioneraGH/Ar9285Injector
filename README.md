## Ar9285Injector

This kext is used for Atheros 9285 Wireless Lan Adapter.

Ar9285 is an adapter which macOS supports natively, but there are only about 6
ids in Atheros40.kext's plist file. I make this plist to add support for more
9285 devices. Once this kext is injected, we do not need to patch the origin
IO802Family.kext perhaps, including KextsToPath in Clover.

