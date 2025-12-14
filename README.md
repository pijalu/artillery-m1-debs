# Artillery M1 Upgrade Files Archive

This repository contains historical upgrade files for the Artillery M1 printer. These files serve as an archive of previous firmware and software releases that can be used to downgrade or revert your printer's software as needed.

## Contents

The repository includes `.deb` packages for various components of the Artillery M1 ecosystem:

- `Yuntu_m1-Yuntu_m1_ALGO_APP-*`: Artillery AI application
- `Yuntu_m1-Yuntu_m1_client_deb-*`: Client software packages
- `Yuntu_m1-Yuntu_m1_s1_client_deb-*`: S1 client software packages
- `Yuntu_m1-Yuntu_m1_test-*` and `Yuntu_m1-Yuntu_m1_s1_test-*`: Test version packages

## Purpose

These files are maintained to allow users to:
- Revert to previous versions if newer updates cause issues
- Access older versions for compatibility reasons
- Maintain a backup of official release versions

## File Naming Convention

Files follow the pattern: `{package_name}-{version}.deb`

## Caution

Before reverting to older versions:
- Ensure compatibility with your hardware revision
- Backup any important custom configurations
- Understand that reverting may remove previously applied security patches or bug fixes

## License

This repository merely archives existing upgrade files. Any licensing terms associated with the original firmware/software remain in effect.
