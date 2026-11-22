Changes for kenwood-ddx57-firmware-update-guide
===============================================

Newest first. Versioning is MAJOR.MINOR.PATCH.

1.0.3 - 2026-11-21
------------------

  - pdf: show Kenwood's MCU string in monospace in Verify, as the APP one
    already is
  - pdf: note Kenwood's listed size, 48.5 MB, beside ls -l in the download
    check
  - pdf: set the subtitle on two balanced lines instead of leaving
    "Windows" alone on the second
  - readme: version and checksum


1.0.2 - 2026-11-21
------------------

  - pdf: replace the note that suggested trying a USB 3 stick first with
    Kenwood's rule that other USB specifications cannot update
  - pdf: add the confirmation page that Agree (Download) opens, and have
    step 4 compare the archive's file list rather than expect three files
  - pdf: word the security row as Kenwood does (security function) and
    spell out "confirmation page" in the USB rows
  - pdf: name the Linux tools the commands need, with the pacman line
    that installs them
  - pdf: name the volume KWUPDATE in the macOS and Windows rows; cite
    Apple's partition schemes page for Master Boot Record and Microsoft
    Learn for the 32 GB FAT32 limit
  - pdf: drop the DDX5707S_09.zip name and size, which Kenwood no longer
    lists
  - pdf: show the APP target in Kenwood's notation, like the MCU one, and
    say in Verify what Kenwood prints
  - pdf: name the SETUP screen as the instruction manual does, without the
    unverified gear shape, and cite the manual (B5H-0358-23)
  - pdf, readme: word the unusable-receiver warning as Kenwood does: an
    error during the update
  - pdf: re-check every web source on 2026-11-21; the support index row
    keeps its 2026-10-03 reading
  - pdf: Figure 2 marks the update window rather than the car; Figure 4's
    step 4 arrow now lands on step 5
  - pdf: regenerate the whole file: one font subset per face, bullets and
    checklist text in the body face, code shading within the margins
  - readme: version, checksum, APP target notation, Apple page title,
    support index read date, four new sources


1.0.1 - 2026-10-29
------------------

  - readme: refresh the PDF checksum; drop the DOCX one, as only the PDF
    ships; name the MCU 210521_1A/1B variant
  - pdf: print the version in the page header, date the document metadata,
    and cite the Software Information photo without its file name
  - pdf: drop the unused, unembedded Helvetica resource
  - pdf: name Kenwood's second DDX5707S/DDX57S row (MCU 210521_1A/1B, APP
    only) and add the APP 220124 + MCU 240525_1E outcome
  - pdf: label Figure 2's reboot slot, fit Figure 3's title in its box, and
    mark Figure 1's layer roles as inferred
  - pdf: cite the confirmation page for the USB rows, print Kenwood's
    wildcards, and link the source URLs, breaking long ones at / or &
  - readme, pdf: link Apple's Disk Utility page without the Latin America
    locale and the macOS 10.15 edition
  - changelog: kernel.org layout


1.0.0 - 2026-10-04
------------------

  - guide: initial release for Kenwood DDX5707S_10.zip (APP 260402,
    MCU 240525_1E)
  - guide: eligibility, requirements, download, USB prep, two-phase
    procedure
  - guide: verify step with outcome table, troubleshooting, two checklists
  - guide: every factual line verified against kenwood.com on 2026-10-03
  - guide: inferences and assumptions labeled as such in the text
  - pdf: 7 pages, Letter, four figures (layers, timeline, USB state, flow)
  - docx: editable copy of the same content
  - license: CC BY 4.0 (LICENSE at the repo root)
