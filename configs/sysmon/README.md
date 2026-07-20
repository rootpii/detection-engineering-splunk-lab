# Sysmon configuration

This lab uses Olaf Hartong's [sysmon-modular](https://github.com/olafhartong/sysmon-modular) pre-built `sysmonconfig.xml` — unmodified from upstream, not a custom-tuned version. See `docs/03-endpoint-telemetry.md` for the reasoning behind choosing this over Microsoft's default config or SwiftOnSecurity's.

**Source:**
```
https://github.com/olafhartong/sysmon-modular/blob/master/sysmonconfig.xml
```

**Installed config hash** (confirmed via `Sysmon64.exe -c` on WIN10-01, verified against the deployed file):
```
SHA256=4516404FA30EE87CEA558567820CDC78863CC4AB07889519E49EAC3CCA92E0D2
```

Correction: an earlier version of this doc had a transcription error in this hash, misread from a terminal screenshot (0/D, 8/B, C/E confusion in a small monospace font). The value above is computed directly from the actual deployed file and is the authoritative one.

The raw file is included in this folder (`sysmonconfig.xml`) — it's the unmodified upstream file, not a custom-tuned version.
