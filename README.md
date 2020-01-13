# Learning SSML

Besides just inserting variables into speech, you can edit: speed, pitch, emphasis, read-as, audio, pauses/breaks, and even play sounds in parallel with specified time delays! ([and more](https://developers.google.com/assistant/actions/reference/ssml))

Just one of the things I'm learning. https://github.com/hchiam/learning

Example:

```html
<speak>
  Edit this to try it for yourself! Each parallel item must have media surrounding it and a globally-unique ID.
  <par>
    <media xml:id="1">
      Saying something while a sound is playing.
    </media>
    <media xml:id="2">
  <audio src="https://actions.google.com/sounds/v1/cartoon/cartoon_boing.ogg"/>
    </media>
  </par>
  <par>
    <media xml:id="3">
      <speak>Hello there</speak>
    </media>
    <media xml:id="4">
      <speak>Hi, how are you?</speak>
    </media>
  </par>
  <par>
    <media xml:id="5">
      <speak>Oh sorry you go first</speak>
    </media>
    <media xml:id="6">
      <speak>No you first, oops. haha</speak>
    </media>
  </par>
  End of awkward conversation
</speak>
```

## Links to learn more:

https://developers.google.com/assistant/actions/reference/ssml

https://www.smashingmagazine.com/2019/12/voice-skills-google-assistant-amazon-alexa
