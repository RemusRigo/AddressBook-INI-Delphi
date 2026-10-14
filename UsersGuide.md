# AddressBook-INI: User's Guide

> AddressBook-INI is **on hold**: it is an old project (2008), published as found.



## Downloads & Runtimes

Download the latest release from the [Releases page](https://github.com/RemusRigo/AddressBook-INI-Delphi/releases).

|Folder|Architecture|Required Runtime|
|-|-|-|
|`Win32`|32-bit|none (native Windows app)|
|`Win64`|64-bit|none (native Windows app)|



## Install

AddressBook-INI is portable: there is no installer.

1. Copy `AddressBook.exe` (and the `Language` folder, if the release has one) to a folder where you have write access,
   for example `D:\My Apps\AddressBook\`.
2. Double-click `AddressBook.exe`.



## Usage

* The main window lists the contacts. Use the toolbar to add a contact, edit the selected one, or open the **Alarm**.
* **Alarm** shows a calendar of the current month with the contacts' birthdays.
  Run `AddressBook.exe /alarm` (e.g. from the Startup folder) to open only the alarm.
* **Options** → **Language**: choose the language of the user interface.

|Folder (next to `AddressBook.exe`)|Content|
|-|-|
|`Contacts\`|One `.ini` file per contact|
|`Language\`|Language files (`.ini`)|



## Uninstall

Delete the folder (copy the `Contacts` folder first if you want to keep your contacts).
