# Manage Series Plugin
[![MobileRead][mobileread-image]][mobileread-url]
[![History][changelog-image]][changelog-url] 
[![License][license-image]][license-url]
[![calibre Version][calibre-image]][calibre-url]
[![Status][status-image]][status-image] 

## Overview

This plugin offers a GUI allowing you to quickly create and edit your series column values for your selected books using either drag/drop or keyboard shortcuts. With the current deprecation of various Calibre series metadata sources (except when using the Goodreads metadata plugin) users may find the need for more manual editing of their series information.

It is intended as a convenience alternative to the editing the series column in the library view, where the [] square brackets must be very carefully edited within. This can get painfully repetitive particularly for renumbering large series.

You may also find it more convenient than the careful mouse selection ordering required by the bulk metadata edit dialog (which also does not allow for .1 type series values).

## Main Features

- Supports both the built-in Calibre series column and optional custom series columns.
- Use Alt+Up/Down arrow keys or drag/drop to move books up/down the list.
- Use Alt+Left/Right to change the indent level to number books at .1 or .01, such as when you have related short stories.
- Lock series indexes when renumbering to intentionally allow for gaps with missing books.
- Remove books from the list if they are not to be considered part of the series renumbering.
- Option to add empty books to fill in your series gaps.
- Ability to edit the titles and publication dates.
- Right-click options to sort by original series index, series names or by publication date.
- Right-click options to perform Search the Internet type browser launching to likely useful series information websites, such as FantasticFiction, Goodreads, Google and Wikipedia.


## Dialog Options

| Option  | Description |
| --------| ----------- |
| Series Column | Choose which series column to set with this dialog, includes custom columns.
| Series Name | The name of the series to apply to this column.
| Start At | Series index renumbering to start from this value.
| Move book up/down | Shortcut keys Alt+Left or Alt+Right to move books up/down one position.
| Lock to index value | Lock series index for this book to a specified value.
| Unlock series index | Unlock the series index for this book.
| Add empty book | Add an empty book to the list as a placeholder.
| Remove book | Remove book from the dialog so as to not have series changed.
| Move decimal left/right | Adjust the decimal position of index e.g. 2 -> 2.1 -> 2.01

## Development / Contributions

All kiwidude's calibre plugins are now developed and maintained in GitHub at:
- https://github.com/kiwidude68/calibre_plugins

Please see the README.md and CONTRIBUTING.md at the above site for more information.


[mobileread-image]: https://img.shields.io/badge/MobileRead-Plugin%20Thread-blue?logo=data:image/x-icon;base64,AAABAAEAEBAAAAEAIABoBAAAFgAAACgAAAAQAAAAIAAAAAEAIAAAAAAAQAQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAns32/zqT5v8SeeD/Enng/xJ54P8SeeD/LYvl/3+78v8AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAZazv/xJ54P8SeeD/Enng/zqT5v9Jm+n/HoLi/xJ54P8SeeD/OpPm/wAAAAAAAAAAAAAAAAAAAAAAAAAAzub7/xJ54P8SeeD/Enng/4/D9P/p6en/0tLS/8Tc8P8SeeD/Enng/xJ54P+Pw/T/AAAAAAAAAAAAAAAAAAAAAL3e+v8SeeD/Enng/xJ54P+93vr/Wlpa/zc3N/8AAAAAEnng/xJ54P8SeeD/f7vy/wAAAAAAAAAAAAAAAAAAAAAAAAAAHoLi/xJ54P8SeeD/T3+r/yQkJP9+jpz/Zazv/xJ54P8SeeD/Enng/73e+v8AAAAAAAAAAAAAAAAAAAAAz8Kt/66uof+Gj4L/ho+C/5SKb/+Vh2j/ho+C/4aPgv+Gj4L/ho+C/5OVgv+6qYP/yryi/wAAAAAAAAAAp5BW/6eQVv+nkFb/p5BW/6eQVv+nkFb/p5BW/6eQVv+nkFb/p5BW/6eQVv+nkFb/p5BW/6eQVv8AAAAA6ePb46eQVv+nkFb/p5BW/6eQVv+nkFb/xLWY/8/Crf/Pwq3/vq6N/7qogv+6qIL/uqiC/7qogv+nkFb/5uDW/+bg1v+nkFb/p5BW/6eQVv+nkFb/p5BW/+zn4f///////////8zMzP92dnb/VFRU/9nZ2f//////taJ5/8/Crf/m4Nb/p5BW/6eQVv+nkFb/p5BW/6eQVv/m4Nb////////////MzMz/k5OT/8zMzP/z8/P//////8S1mP/EtZj/5uDW/6eQVv+nkFb/p5BW/6eQVv+nkFb/oZ6Z/5OTk//m5ub/////////////////8/Pz/3Z2dv9xcHD/j4h7/9rRwf+nkFb/p5BW/6eQVv+nkFb/VVNP/8zMzP/z8/P/dnZ2/9nZ2f///////////5OTk//z8/P//////3Rxa//Pwq3/p5BW/6eQVv+nkFb/p5BW/2FgYP///////////76+vv/MzMz///////////+ioqL/oqKi/76+vv91b2X/z8Kt/6eQVv+nkFb/p5BW/6eQVv+JfWX/bGtq/4WFhf+FhYX//////////////////////76+vv++vr7/taJ5/8/Crf+nkFb/p5BW/6eQVv+nkFb/p5BW/8m7ov//////+Pb1/+bg1v/g2Mz/z8Kt/8/Crf+6qIL/uqiC/6eQVv/m4Nb/uqmD/7qpg/+nkFb/p5BW/6eQVv+nkFb/rZZh/7qpg/+/r43/z8Kt/8/Crf/m4NYd5uDWVQAAAAAAAAAA8A8AAOAHAADAAwAAwEMAAOADAADAAQAAgAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAMAAA==
[mobileread-url]: https://www.mobileread.com/forums/showthread.php?t=125729

[changelog-image]: https://img.shields.io/badge/History-CHANGELOG-blue.svg
[changelog-url]: CHANGELOG.md

[license-image]: https://img.shields.io/badge/License-GPL-yellow.svg
[license-url]: ../LICENSE.md

[calibre-image]: https://img.shields.io/badge/calibre-2.0.0-green
[calibre-url]: https://www.calibre-ebook.com/

[status-image]: https://img.shields.io/badge/Status-Stable-green