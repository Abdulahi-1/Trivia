# Trivia_IOS

Submitted by: Abdulahi Abdi

Trivia_IOS is an iOS application that allows users to test their knowledge by answering a set of trivia questions. The app fetches questions from the Open Trivia Database API and presents them in a simple interface where users can select answers, track their progress, and view their score at the end of the game. It demonstrates networking, JSON decoding, UI updates, and data passing in iOS using Swift and Storyboard.

Time spent: 7 hours spent in total

## Required Features

The following **required** functionality is completed:

- [X] User can view and answer at least 5 trivia questions.
- [X] App retrieves question data from the Open Trivia Database API.
- [X] Fetch a different set of questions if the user indicates they would like to reset the game.
- [X] Users can see score after submitting all questions.
- [X] True or False questions only have two options.

The following **optional** features are implemented:

- [X] Allow the user to choose a specific category of questions.
- [X] Provide the user feedback on whether each question was correct before navigating to the next.

The following **additional** features are implemented:

- [X] Improved UI styling for question and answer presentation.
- [X] Added a reset button on the results screen for easier replay.
- [X] Smooth transitions between questions to improve user experience.

## Video Walkthrough

[Video Walkthrough Link Here]  

## Notes

One challenge I faced was handling the API response and ensuring the trivia questions displayed correctly, especially since the API returns HTML-encoded strings (e.g., `&quot;` instead of quotes). I resolved this by decoding the HTML entities in the question text before displaying them in the UI.Another challenge was resetting the game with a fresh set of questions without reloading the entire view controller. I solved this by structuring the API call into a reusable function and calling it whenever the reset button was tapped. The outcomes were that the app now consistently shows clean, readable questions and allows users to reset and play multiple rounds smoothly. This made the app feel more polished and user-friendly.

## License

    Copyright 2025 Abdulahi Abdi

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
