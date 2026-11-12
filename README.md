# Activity 15 – API-to-Cloud Trivia Showdown

## Project Description
This Flutter application retrieves five easy multiple-choice trivia questions from the Open Trivia Database API. Users can answer questions, receive immediate feedback, track their score, and replay the round.

## Features
- Fetches five trivia questions using HTTP.
- Checks HTTP status and API response code.
- Parses JSON question and answer data.
- Cleans encoded HTML entities.
- Shuffles multiple-choice answers.
- Displays loading and error states.
- Shows green correct-answer and red incorrect-answer feedback.
- Prevents answering the same question more than once.
- Tracks the final score out of five.
- Allows users to play again.

## Score Sync
This project uses the classroom score-sync simulation. The app displays a confirmation after a simulated delay. **No backend request was sent, and no score was saved remotely.**

## API Used
Open Trivia Database:

https://opentdb.com/api.php?amount=5&category=9&difficulty=easy&type=multiple

## Screenshots and Evidence
See the `screenshots/` folder for evidence of:
- Loading state
- Trivia questions
- Correct and incorrect answer feedback
- Question progression
- Final score
- Simulated score synchronization

## Testing
- Flutter app launched and tested.
- Five-question round tested.
- Correct and incorrect answers tested.
- Score tracking and replay tested.
- Score-sync simulation tested.
- Flutter analyzer and test results: add your actual results here.

## Limitations
Score synchronization is simulated rather than connected to a real cloud backend. The app retrieves questions from the live API and requires an internet connection to load a new round.
