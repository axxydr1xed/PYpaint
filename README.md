<div align="center"><img src="[https://www.github.com/axxydr1xed/PYpaint](https://github.com/axxydr1xed/PYpaint/blob/main/assets/Screenshot_20260820_013511.png?raw=true)"></div>
# PYpaint
## (it's pronounced Pie-Paint)
A simple drawing program built entirely with Python, primarily using the `turtle` library and its `tkinter` backend.

Latest version: 1.0 Volga
## features
- 11 colours to pick from
- Quick screen clear keybind
- Included user manual (in the program's intro and help text)
- Simple undo keybind to erase one latest stroke
- Changeable brush size
- Text-only UI
- Simple keybinds

# Q&A
<details>

## questions that will likely be asked
### why PYpaint?
It's simple and very lightweight. To be honest, that's, like, the only reason to pick PYpaint over something like Krita.
### why PYpaint, the name?
Sounds cool. `PY` stands for Python, though. Also, while we're at it, if you're referring to PYpaint, please keep the formatting of the name either exactly like the original *(PYpaint, with the first P and Y capitalised)*, in lowercase *(pypaint, no capitalisation)*, or in UPPERCASE *(PYPAINT, with all the letters capitalised)*.
### are there any libraries I need to download?
Nope! It only uses the `turtle` library that is included with the latest version of Python.
I also mentioned `tkinter`, but I didn't directly import it, it comes with `turtle`.
### what versions of Python does PYpaint work on?
Certainly on the latest one, didn't test anything else. You could test it for me and tell me to list it.

## less likely, but still possible questions
### why are the codenames just names of rivers?
Y'know how Android has its versions named after sweets ever since, like, 4.0? Same thing, but for rivers. Codenames are cool - and a consistent theme in them is even cooler!
### why are so many features unimplemented?
Look, I'm a teenager doing this as a hobby. I just got tired of doing stuff with this script after like 3 hours of making it non-stop, I'll add everything that's planned at some point.

**THAT SAID**, don't expect something huge or even slightly professional drawing program oriented, I'm not doing all that! This is just a project I randomly came up with, not something I'll polish forever and ever, y'know?

Though, I could say this is probably my most complex project yet, even if the length or complexity of the code doesn't agree with that statement.
### why is there no graphical UI aside from keybind feedback?
Why do you think? I just suck at Python. Well, okay, maybe I'm not THAT bad... but I'm not good enough for such big-shot things as UI, y'know.
## source code questions
### why are you using camelCase in your python project?
In my opinion it just looks better than snake_case. Yeah, that's really it. Also, my last personal non-public coding project involved JavaScript, and camelCase is **the** thing in there.
### why aren't you following PEP8 much?
Why should I? I mean, it's not mandatory to follow PEP8 for my stupid little MSPaint remake to work, y'know.
</details>

# Versions
<details>

## 1.0 Volga
Initial release.
Added:
- All the keybinds:
<details>
 
 - Help text, triggered with `H`;
 - `=` and `-` to increase and decrease the brush size; `Ctrl+=` and `Ctrl+-` to show the current brush size on the screen;
 - `C` to clear the canvas;
 - `X` to quit;
 - `Ctrl+Z` to Undo;
 - `E` to cycle brush colour; `Shift+E` to cycle brush colour back; `Ctrl+E` to show the current brush colour on the screen;
</details>

- Forced fullscreen (probably will change that to toggleable *At Some Point™*)
- An intro
- Textual feedback
- The drawing system (like, yeah. crazy, right?)
</details>
