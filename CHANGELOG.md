> `Changelog:`
> - All significant changes to this project will be documented here.
---

> [3.49.1] - `20250603`
>
> - Updated `customize.sh` and added `verify.sh` for module file integrity.
> - Removed logging system: Eliminated log file creation and detailed logging for cleaner execution
> - Removed notification system: No more Android notification popups during deployment process
> - Dynamic module directory detection: Script now uses its own location instead of hardcoded /data/adb/modules/SDMAID path
> - Added boot timeout protection: 300-second timeout prevents infinite waiting for boot completion
> - Enhanced architecture support: Added support for architecture aliases
> - Improved error handling: Added early exit conditions for better failure detection
> - Enhanced package validation: Verify target package exists before processing installation
> - Added installation counter: Track and validate successful library deployments
> - Optimized file operations: Better error checking and handling for copy operations
> - Streamlined code structure: Removed unused variables and simplified conditional logic
> - Performance improvements: Reduced resource usage and faster execution without logging overhead
> - Removed module property parsing: No longer reads module name from module.prop file
---

> [3.49.1] - `20250310`
>
> - Libsqlite version `3.49.1`.
> - Change module thumbnails.
> - Logs are stored in `data/adb/modules/SDMAID`.
---

> [3.49.0] - `20250224`
>
> - Initial release.
> - Libsqlite version `3.49.0`.
---