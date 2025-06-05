# Project 1 - *Wordle*

Submitted by: **C. Alejandra Carreon**

**Wordle** is an app that simulates a guessing word game written on swift for IOS.

Time spent: **4** hours spent in total

## Required Features

The following **required** functionality is completed:

- [X] App displays a keyboard on the screen
- [X] When tapping on the keyboard, a letter is shown or deleted (letter selected)
- [X] User can play a basic version of Wordle, with different goal words each time

The following **optional** features are implemented:

- [X] Improve and customize the user interface by adding a launchscreen and app icon
- [X] Run the app on a device rather than in the simulator

## Video Walkthrough

<div>
    <a href="https://www.loom.com/share/05ae487f905f4fd19767991bff8d7e26">
      <p>Xcode - Wordle — Wordle.xcodeproj - 5 June 2025 - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/05ae487f905f4fd19767991bff8d7e26">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/05ae487f905f4fd19767991bff8d7e26-3104cf5e1afac769-full-play.gif">
    </a>
  </div>

## Notes

Notes to self - Wordle Project CodePath iOS 101
Exercise 4: Tried assigning closure to class instead of instance, fixed with cell.didSelectString = didSelectString
Exercise 5: Worked fine, used didSelectString?(string) for safety
Exercise 6: Called method on class instead of instance, fixed by calling on cell
Exercise 7: Forgot to assign result of scaledBy, fixed with cell.transform = cell.transform.scaledBy(...)
Exercise 9: Used UIColor without labels, fixed with labeled init and added .cgColor for borderColor


## License

    Copyright [2025] [C. Alejandra Carreon]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
