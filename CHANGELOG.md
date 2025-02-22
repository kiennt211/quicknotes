# Changelog

## [0.7.1] 2021-03-19
- Fix php 7.3 support, as it accidentally used more modern features.
- Introduce initial unified search support, that search by title and content.
- Implements some consistent urls, which allow you to mark a note, tag or color
  as a favorite in the browser to easily access to them.

## [0.7.0] 2021-03-19
- Bump version to move the numbering away from the version nc20 or lower.
- New Macedonian translation thanks to Сашко Тодоров.
- Update Portuguese (Brazil) and Polish translations. Thanks to the translators.

## [0.6.6] 2021-03-19
- Fix on NC20

## [0.6.5]: 2021-03-18
- Emergency release to truly enable NC21. Thanks @nursoda for report it on
  issue #57

## [0.6.4]: 2021-03-18
- Initial Nextcloud 21 support.
- Add new api for uploading attachments. For now only used in the Android
  client.
- Update Portuguese (Brazil) thanks to flaviove.

## [0.6.3]: 2020-10-31
- Fix thumbnail when pretty url is disabled. Issue #48
- Update French translation thanks to Thovi98

## [0.6.2]: 2020-10-27
- Enable Nextcloud 20 support.
- Use the same url from thumbails that Photos.
- Update French translation thanks to Thovi98
- New Portuguese (Brazil) translation thanks to THOMAS COUTO ROCHA

## [0.6.1]: 2020-10-03
- Improve API needed to implement the android client.
- Register nextcloud capabilities to check api versions.
- Fix response when dont have notes. Issue #44.
- Update German translation thanks to Lars Seidler.
- Update German (Germany) translation thanks to Lars Seidler.
- Update Russian translation thanks to Rusalan Kortikov.
- Update Polish translation thanks to Valdnet Valdnet.

## [0.6.0]: 2020-06-17
- Enable sharing of notes as read-only between users. Issue #3, #16 and PR #8. Thanks to Vinzenz Rosenkranz
- Fix many untranslated strings. Issue #31 and #32
- Add a small modal dialog to change the color of the note.
- Add an option to select the default color for new notes.
- First version of an API for third-party applications
- Modernize some code, clean others and try to improve some css styles.
- Update Italian translation thanks to Valerio Pulese.
- Update Spanish translation thanks to Matias De lellis.

## [0.4.0]: 2020-06-14
- Implement attachments to notes.
- Fix the icon that marks the color of the modal note.

## [0.3.0]: 2020-06-08
- Implement pin notes to keep notes always in view.
- Add confirmation dialog to cancel edition. Part of issue #27.
- New links are created to open in another tab.
- Translate many new strings. Part of issue #32.
- Improvements in styles and animations.
- Move part of the code to the new Nextcloud standards.
- Update German (Germany) translation thanks to Lars Seidler

## [0.2.4]: 2020-08-05
- Add French translation thanks to Aymo XXX.
- Update German translation thanks to lhsei.
- Support NC19.

## [0.2.3]: 2020-02-06
- Drop support to NC15 in line with Nextcloud.
- Add Russian translation thanks to Rusalan Kortikov.
- Add Polish translation thanks to Valdnet Valdnet.

## [0.2.2]: 2020-01-08
- Support NC18.
- Fix Italian translation thanks to Valerio Pulese.

## [0.2.1]: 2019-11-14
- Support NC15 again. It's the stable version.
- Update the navigation menu correctly with the new tags.
- Fill the tag dialog with the modal and not replace it with those in the db.

## [0.2.0]: 2019-11-12
- Implement notes tagging support and filter with it.
- Fix calling exponentially to save notes when pressed Alt+Return.
- Update spanish translation

## [0.1.10]: 2019-11-02
### Added
- Add Italian translation. Thanks to @albanobattistella
- Use fullscreen modal on small screen. Issue #23
- Add an small fade animation when hide the modal note.
- Install libs using npm to ensure versions of handlebars.
- Use transifex to translations. Please, help to it.

## [0.1.9]: 2019-08-21
### Added
- Indicate support for NC 17.
- Update app screenshots.

## [0.1.8]: 2019-08-15
### Added
- Add Alt+Return as keyboard shortcut to save note. Issue #21
- Show an animation when show the modal to editing notes.

## [0.1.7]: 2019-04-23
### Added
- Just bump versio to fix NC pattern

## [0.1.6.1]: 2019-04-23
### Added
- Initial Nextcloud 16 release

## [0.1.6]: 2019-02-12
### Added
- Initial Nextcloud 15 release
- Show an spinner while loading notes
- Add a confirmation before deleting a note
- Do happy to NC app:check
- Fix title on new notes.
- Don't collapse color menu when click on empty area

## [0.1.5]: 2018-10-13
### Added
- Initial Nextcloud 14 release.

## [0.1.4]: 2018-08-29
### Added
- Some styles fixed.

## [0.1.3]: 2018-04-26
### Added
- Some styles fixed.

## [0.1.2]: 2018-04-17
### Added
- Initial Nextcloud release.
- Use medium-editor as basic rich editor
- German translation from @v1r0x
- Spanish translation.

## [0.1.0]
### Added
- Implement search on notes.
- Rename 'Add note' item to 'New note' and put first on navigation.
- D'Oh!. Fix animation when append or remove notes.

## [0.0.8]
### Added:
- Fix database schema migration.

## [0.0.6]
### Added
- Several design fixes, thanks to v1r0x.
- Highlight current color on edit mode, thanks to v1r0x.
- Put color on own database with relationship over on notecontroller.
- Highlight current color selection on navigation filter.
- Show all notes when remove one.
- Fix: Redraw content to show first note.

## [0.0.4]
### Added
- Show Animation when add or remove notes without redraw everything.
- Show all when append a new note.
- Add the new notes in the proper position.
- Positioning the modal editor in the position of the original note.
- Hide editor when click outside modal.
- Not refilter anything when cancel edit.
- Add Ocsid and useful data.

## [0.0.2]
### Added
- Initial version:
- Just text notes and filter by color..
- Fix version.
