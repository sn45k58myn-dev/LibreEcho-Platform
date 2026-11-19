# Frozen source history

The adjacent bundle preserves only the new source commits above upstream `59d657c0f42b2cbc821b733991b911d8a5969f2c`. Its exact source head is `99197eff816d2696cc8760a4a1cd86cc4fe216b0`. Verify with `git bundle verify tested-source.bundle`, then fetch `HEAD` locally.

The original upstream commit must be available in the clone. If a shallow clone omits it, fetch that exact upstream base before verifying. No private signing seed, device data or firmware image is included.
