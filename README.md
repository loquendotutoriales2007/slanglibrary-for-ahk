Slang to Formal Text Expander (AutoHotkey v2)

This script utilizes AutoHotkey (AHK) to automatically and instantly expand common internet slang, text messaging shortcuts, and professional acronyms into their formal, full-length phrases.

The goal is to help maintain a professional and consistent writing style across all applications (email, documents, chat, etc.) by correcting casual shorthand as soon as it's typed.

🚀 Setup and Requirements

This script is written for AutoHotkey v2 (AHK v2).

Download AutoHotkey v2: If you don't already have it, download and install the latest v2 release from the official AutoHotkey website.

Save the Script: Save the contents of the slang_expander.ahk file (from the Canvas editor) to your computer.

Run the Script: Double-click the saved .ahk file. The script will start running in the background, indicated by a new icon in your system tray (usually marked with an 'H').

The script is now active and will perform instant text replacements in any program where you type.

📝 Key Examples in Action

The script uses a simple syntax (:*:shortcut::Expanded Phrase) which replaces the shortcut instantly as you type it.

Category

You Type

Result (Instant Expansion)

Texting

btw

by the way

Texting

idk

I don't know

Texting

hmu

contact me

Slang

wanna

want to

Slang

cuz

because

Slang

smh

shaking my head in disappointment

Business

asap

as soon as possible

Business

eod

end of day

Business

kpi

key performance indicator

Academic

i.e.

that is (id est)

Academic

e.g.

for example (exempli gratia)

Academic

phd

doctor of philosophy

🔧 Customization and Editing

You can easily modify this script to add your own shortcuts or change existing expansions.

The core format is:

:*:shortcut::Expansion Text


Tips for Editing:

Instant Replacement: The :*: prefix ensures that the text replacement happens immediately, without requiring you to hit space, enter, or punctuation afterward.

Case Sensitivity: By default, AHK hotstrings are not case sensitive. If you type BTW, it will still expand to by the way.

Adding New Terms: Simply add a new line under the appropriate section header (or create a new section) and use the format shown above.

Reloading: After saving any changes to the .ahk file, you must reload the script. To do this, right-click the AHK icon in your system tray and select "Reload".
