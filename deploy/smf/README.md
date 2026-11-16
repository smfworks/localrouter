# SMF Works site files

Site-specific settings kept apart from the generic deploy kits, so the kits stay upstream-friendly.

- `strix-halo.env`: our Strix Halo workstation for `deploy/strix-halo` (model directories that already exist under
  `$HOME`, the voice, the machine label). Use: `SITE=deploy/smf/strix-halo.env deploy/strix-halo/start.sh`.

No credentials, hostnames, addresses or user names belong in these files.
