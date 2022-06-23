# multi-line-dialogue
Want to have multiple lines of dialogue to clickthrough with a little typewriter effect? Here you go!

// STEPS TO BUILDS (I tried my best ;_;) //
1. Make your UI screen and dialogue box per Sherveen's tutorial. I also pulled layout numbers from this video: https://www.youtube.com/watch?v=8oTYabhj248
2. Add in the Dialogue.cs and the ShowDialogueOnTriggerEnter.cs into your assets.
3. Add Dialogue.cs to your DialogueBox itself (not the TMPro beneath it).
4. Drag the TextMeshPro game object into the script's "Text Component" box.
5. In the "Lines" section under your script, add as many rows of dialogue as you like.
6. Set your Text Speed. I set mine to .04 because it felt fast enough but you do what your heart desires!
7. Navigate to the game object that will trigger the dialogue.
8. Add the new ShowDialogueOnTriggerEnter.cs script onto this game object.
9. Under the script section, drag your DialogueBox into the "Dialogue" section.
10. Press play and hope that it all works and reach out to me if you have any questions so I can try to help!

// NOTE //
Using this does not require a Dialogue Manager. If you're using the Dialogue Manager script we have from class, you'll need to delete that first.
Technically the Dialogue.cs file is the new Dialogue Manager but to be honest, I don't know how or why it works that way.
