# Spacereed 1.0 TEST
Native Android No Three circle-shading puzzle. Android8+ (min26), target35. Package com.gg007.spacereed.

## Rules
No Three: tap cells dark or light. Each gold circle touches exactly one dark cell: a circle at a cell center covers one cell, an edge circle two, a vertex circle four. Dark cells cannot share an edge. All light cells connect by edges. Three successive dark cells along a row or column cannot have equal gaps. Diagonals are unrestricted. Twelve unique 5x4 boards and distinct solutions, each with all three circle footprint sizes. Undo/reset/next/levels and saved space palette/dark marks.

## Download and status
https://mega.co.nz/#!tVl20I6D!UyRioRRCq3DIzjmmkhuQhykFyHDetPAJmgcoZ0lwgUw
APK SHA256 e9c134bf87d157f626d0ca2f079889ab4e34013d123e9f3e77887f675e042845; 16878 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous download bytes match.

## Checks
Independent coordinate-set oracle uses pairwise adjacency, ordered triples, set connectivity and coordinate-based circle footprints. It agrees with production bitmask flood-fill and successive-gap scan for all12582912 masks across twelve boards. Twelve distinct clue arrays and unique solutions; bounds, invalid levels/masks, solved lock, solve/undo/reverse replay pass. Actual archived generator regeneration and archived Java tests pass. Drawing-adapter cell taps, navigation, saved settings, completion marks, next/levels and privacy pass. Game/solved/menu/settings/privacy/levels drawing pixels inspected, not phone screenshots. Phone runtime, performance and external-browser handoff QA remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Live803-entry registry,121 recovered partial READMEs and semantic review of all147 prior studio cards found no No Three match. Trifen forbids consecutive monochrome triples including diagonals and gives one dark circle per room. Spacereed instead forbids equal spacing among successive dark cells only, has no region quotas or diagonal/light-triple restrictions, and uses local 1/2/4-cell circle footprints, isolated darks and light connectivity. Brookmere counts darks around grid vertices but has numbered count clues and no equal-spacing or dark-isolation requirement. Known Nikoli No Three genre, not a global invention; recovered corpus is partial. Rules https://ericfox53.blogspot.com/2025/06/510-no-three.html https://www.4x1om.org/no-three-guide https://scrapbox.io/puzzle-pedia/%E3%83%8E%E3%83%BC%E3%82%B9%E3%83%AA%E3%83%BC .

## Build
JDK17 and AndroidSDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. Board.java embeds the generated clues and solutions. javac -d /tmp/space-test src/com/gg007/spacereed/Board.java BoardTest.java and java -cp /tmp/space-test com.gg007.spacereed.BoardTest. bash build.sh builds an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to private original signing inputs. No credentials in source. Release build settings, signed TEST artifact, not final store release.

## Privacy and branding
Spacereed runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Space palette, dark marks and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 icon byte-equal to original. Menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and websites
Complete source and APK privately preserved at https://files.instinct.com/kcicylrexfqg-spacereed-source-archive, including exact cumulative148-card studio and published catalog/studio sources/updater. Repository https://github.com/iLanis-agent/spacereed holds README only; full Git source commit pending. Both website publications checked separately. No Pages settings change or Play rollout. November7,2026.
