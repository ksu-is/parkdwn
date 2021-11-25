# Parkdwn Development Roadmap

## Sprint 1

### GUI
I'd like to get just a basic GUI with a limited toolbar/menubar and an editing space.

### Backend
I want to enable creation of new files, opening of existing files, saving of files, and closing of files without closing the application

**Checklist**
- [x] Standalone window (not browser based)
- [ ] User choice of parent directory location
- [x] Menubar with File and View option
- [x] Ability to create new file,open existing file, save file, and close file
- [ ] Ability to enable/disable live preview


## Sprint 2

### GUI
I want to add an Edit option to the menu bar that can insert bolded or italicized text.

### Backend
I want to add encryption and optional Drobox syncing.  For the Dropbox syncing, I'll also add a warning about folder locations.  If the user decides to enable Dropbox syncing, they'll receive a warning not to turn it on if the parent folder is inside a directory already being synced by another service (the Documents folder on a Mac syncing to iCloud for example), because this can cause issues with one service locking the file to sync at the same time another syncing service is trying to access it.

**Checklist**
- [x] Edit option in menubar
- [ ] Bold option to automatically insert double asterisks
- [ ] Italics option to automatically insert single asterisks
- [ ] Extras option in menubar
- [ ] Option to encrypt parent folder of all notes with 256-bit AES encryption
- [ ] Option to add Dropbox syncing, with a warning about file  placement