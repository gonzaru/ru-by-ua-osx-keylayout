# Russian macOS keyboard layout with Belarusian/Ukrainian letters
Russian keyboard plus some missing Belarusian/Ukrainian letters (є,Є,ї,Ї,і,І,ґ,Ґ,ў,Ў,')

## Modifiers
Shift: ⇧\
Option: ⌥
* ⌥ + э = є
* ⌥ + ⇧ + э = Є
* ⌥ + ё = ї
* ⌥ + ⇧ + ё = Ї
* ⌥ + ы = і
* ⌥ + ⇧ + ы = І
* ⌥ + г = ґ
* ⌥ + ⇧ + г = Ґ
* ⌥ + щ = ў
* ⌥ + ⇧ + Щ = Ў
* ⌥ + ⇧ + 9 = '

## Installation
Move the keyboard layout `RussianPlus.keylayout` and icons file `RussianPlus.icns`\
To `~/Library/Keyboard Layouts/` (current user)\
Or `/Library/Keyboard Layouts/` (for all users)

    git clone https://github.com/gonzaru/ru-by-ua-osx-keylayout.git
    cd ru-by-ua-osx-keylayout/
    # for your current user
    cp RussianPlus.{icns,keylayout} ~/Library/Keyboard\ Layouts/
    # for all users
    sudo cp RussianPlus.{icns,keylayout} /Library/Keyboard\ Layouts/

Log Out your user or restart the computer if necessary.

Enable the new keyboard layout from System Preferences->Keyboard->Input Sources (press + and look for the "Others" section)
