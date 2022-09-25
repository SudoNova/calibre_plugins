# Modify ePub Plugin
[![MobileRead][mobileread-image]][mobileread-url]
[![History][changelog-image]][changelog-url] 
[![License][license-image]][license-url]
[![calibre Version][calibre-image]][calibre-url]
[![Status][status-image]][status-image] 

## Overview

This plugin offers a way to perform certain modifications to your selected ePub files without performing a calibre conversion. This plugin was created a number of months ago and has a history documented in the Development forum on [this thread](https://www.mobileread.com/forums/showthread.php?t=134249).

Performing an ePub->ePub conversion will enforce a number of changes to your ePub, some of which can be undesirable for some users. Examples are the rewriting of CSS, margin modifications, file splitting in undesired places, changes to directory structure etc.

Instead this plugin allows a user specific subset of changes to be performed in isolation without otherwise touching the original ePub's file structure, CSS files etc. Frequently these changes have been performed manually by users either using the Tweak ePub feature (time consuming), by editing in Sigil (which introduces changes/side effects of its own), by doing ePub->ePub conversions, or by saving to disk and reimporting into calibre.

Users may also find it useful to install the [Quality Check](https://www.mobileread.com/forums/showthread.php?t=125428) plugin, which offers the ability to identify ePubs in your library which qualify for many of the modifications this plugin can make.

Refer to the Help file accessed from the plugin dialog for full details on each of the modification options and when you might use them.

## Main Features

- Remove iTunes artifact files
- Remove Calibre bookmark files
- Remove OS artifact files such as Thumbs.db
- Remove unused image files
- Remove missing file entries from the .opf manifest
- Add unmanifested files to manifest
- Remove unmanifested files from ePub
- Remove non dc: metadata from manifest
- Flatten TOC hierarchy in NCX file
- Remove broken link TOC entries in NCX file
- Remove margins from Adobe .xpgt files
- Remove Adobe .xpgt files and links
- Remove Adobe resource DRM meta tags
- Remove all metadata jackets
- Remove legacy metadata jackets
- Add/replace metadata jacket
- Encode HTML in UTF-8 to fix invalid HTML encodings.
- Remove embedded fonts
- Modify @page and body margin styles
- Append extra CSS to each .css file
- Smarten punctuation
- Remove inline javascript and .js files
- Remove html pages containing nothing but broken image links
- Completely remove an existing cover
- Insert a new cover or replace an existing one using your desired proportions/svg choice from Preferences->Output - Options->EPUB
- Update metadata
- Save and restore your preferred settings with a single click
- Remove Adobe pagemaps
- Move metadata jackets to end of book
- Remove excess whitespace and useless markup from HTML
- Remove Kobo-specific artifacts from KEPUBs
- Optional script to run from command line

## Configuration Options

| Column  | Description |
| --------| ----------- |
| Prompt to save epubs | Uncheck this option to have changes applied without a confirmation prompt.

## Development / Contributions

All kiwidude's calibre plugins are now developed and maintained in GitHub at:
- https://github.com/kiwidude68/calibre_plugins

Please see the README.md and CONTRIBUTING.md at the above site for more information.


[mobileread-image]: https://img.shields.io/badge/MobileRead-Plugin%20Thread-blue?logo=data:image/x-icon;base64,AAABAAEAEBAAAAEAIABoBAAAFgAAACgAAAAQAAAAIAAAAAEAIAAAAAAAQAQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAns32/zqT5v8SeeD/Enng/xJ54P8SeeD/LYvl/3+78v8AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAZazv/xJ54P8SeeD/Enng/zqT5v9Jm+n/HoLi/xJ54P8SeeD/OpPm/wAAAAAAAAAAAAAAAAAAAAAAAAAAzub7/xJ54P8SeeD/Enng/4/D9P/p6en/0tLS/8Tc8P8SeeD/Enng/xJ54P+Pw/T/AAAAAAAAAAAAAAAAAAAAAL3e+v8SeeD/Enng/xJ54P+93vr/Wlpa/zc3N/8AAAAAEnng/xJ54P8SeeD/f7vy/wAAAAAAAAAAAAAAAAAAAAAAAAAAHoLi/xJ54P8SeeD/T3+r/yQkJP9+jpz/Zazv/xJ54P8SeeD/Enng/73e+v8AAAAAAAAAAAAAAAAAAAAAz8Kt/66uof+Gj4L/ho+C/5SKb/+Vh2j/ho+C/4aPgv+Gj4L/ho+C/5OVgv+6qYP/yryi/wAAAAAAAAAAp5BW/6eQVv+nkFb/p5BW/6eQVv+nkFb/p5BW/6eQVv+nkFb/p5BW/6eQVv+nkFb/p5BW/6eQVv8AAAAA6ePb46eQVv+nkFb/p5BW/6eQVv+nkFb/xLWY/8/Crf/Pwq3/vq6N/7qogv+6qIL/uqiC/7qogv+nkFb/5uDW/+bg1v+nkFb/p5BW/6eQVv+nkFb/p5BW/+zn4f///////////8zMzP92dnb/VFRU/9nZ2f//////taJ5/8/Crf/m4Nb/p5BW/6eQVv+nkFb/p5BW/6eQVv/m4Nb////////////MzMz/k5OT/8zMzP/z8/P//////8S1mP/EtZj/5uDW/6eQVv+nkFb/p5BW/6eQVv+nkFb/oZ6Z/5OTk//m5ub/////////////////8/Pz/3Z2dv9xcHD/j4h7/9rRwf+nkFb/p5BW/6eQVv+nkFb/VVNP/8zMzP/z8/P/dnZ2/9nZ2f///////////5OTk//z8/P//////3Rxa//Pwq3/p5BW/6eQVv+nkFb/p5BW/2FgYP///////////76+vv/MzMz///////////+ioqL/oqKi/76+vv91b2X/z8Kt/6eQVv+nkFb/p5BW/6eQVv+JfWX/bGtq/4WFhf+FhYX//////////////////////76+vv++vr7/taJ5/8/Crf+nkFb/p5BW/6eQVv+nkFb/p5BW/8m7ov//////+Pb1/+bg1v/g2Mz/z8Kt/8/Crf+6qIL/uqiC/6eQVv/m4Nb/uqmD/7qpg/+nkFb/p5BW/6eQVv+nkFb/rZZh/7qpg/+/r43/z8Kt/8/Crf/m4NYd5uDWVQAAAAAAAAAA8A8AAOAHAADAAwAAwEMAAOADAADAAQAAgAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAMAAA==
[mobileread-url]: https://www.mobileread.com/forums/showthread.php?t=154371

[changelog-image]: https://img.shields.io/badge/History-CHANGELOG-blue.svg
[changelog-url]: CHANGELOG.md

[license-image]: https://img.shields.io/badge/License-GPL-yellow.svg
[license-url]: ../LICENSE.md

[calibre-image]: https://img.shields.io/badge/calibre-2.85.1-green
[calibre-url]: https://www.calibre-ebook.com/

[status-image]: https://img.shields.io/badge/Status-Stable-green