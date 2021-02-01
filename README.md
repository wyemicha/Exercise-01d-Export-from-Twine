# Exercise-01d-Export-from-Twine
Exercise for MSCH-C220, 1 February 2021

A video demonstration of this exercise is available here: [https://youtu.be/m6JNiP9EiDQ](https://youtu.be/m6JNiP9EiDQ)/

This exercise will set up Twine to be able to export a version of an interactive fiction game that could be used in a Python game engine.

Begin by Forking this repository. Check that it has been forked successfully; the repository should now read [your username]/Exercise-01d-Export-from-Twine

Edit the LICENSE and replace BL-MSCH-C220-S21 with your full name. Commit your changes.

Press the green "Code" button and select "Open in GitHub Desktop". Allow the browser to open (or install) GitHub Desktop. Once GitHub Desktop has loaded, you should see a window labeled "Clone a Repository" asking you for a Local Path on your computer where the project should be copied. Choose a location where you will keep the repositories for this class (a C220 folder off your Desktop would be fine). Make sure the Local Path ends with "Exercise-01d-Export-from-Twine" and then press the "Clone" button. GitHub Desktop will now download a copy of the repository to the location you indicated.

Open Twine. In the right-hand sidebar, select "Formats". You should see a list of possible story formats for Twine. In the bar on the top of that window is a button "Add a New Format". Select that now.

The window should now read "To add a story format, enter its address below." Enter https://lazerwalker.com/twison/format.js and press the green "Add" button.

Next, press the "Import From File" button. Navigate to the exercise folder on your computer and select Adventure.html. If you open the story, you will see our familiar story (from an earlier exercise).

If you press the play button, you will see the (also) familiar representation of your game in a web browser. By default, Twine uses the Harlowe 3.1.0, playable, story format, with its black background and link-based navigation. We will now export the story in a format that we can use in our game engine.

Tap on the Adventure menu button on the bottom bar, and select "Change Story Format". Choose Twison 0.0.1 as the new story format. If you now press "Play", your browser will now display a single (JSON) file containing your story.

This content needs to be saved as a text file (named game.json) and added to this repository. You can open a new file in VS Code, copy the contents from the web browser and paste it into the new document. Save the file (in the repository folder) as game.json.

In GitHub Desktop, you should now see game.json highlighted. Add a Summary message at the bottom of that panel, and push the "Commit to master" button. On the right side of the top, black panel, you should see a button labeled "Push origin". Press that now.

If you return to and refresh your GitHub repository page, you should now see that your files have been changed (with a new date).

Now edit the README.md file. When you have finished editing, commit your changes, and then turn in the URL of the main repository page (https://github.com/[username]/Exercise-01d-Export-from-Twine) on Canvas.

The final state of the file should be as follows (replacing my information with yours):
```
# Exercise-01d-Export-from-Twine

Exercise for MSCH-C220, 1 February 2021

A JSON file, describing an interactive fiction game, exported from Twine

## Implementation
Created using Twine 2 and exported with Twison 0.0.1 (https://github.com/lazerwalker/twison)

## References
[Adventure, 1976 by Will Crowther and Don Woods](https://quuxplusone.github.io/Advent/play.html)

## Future Development
None

## Created by
Jason Francis
```
