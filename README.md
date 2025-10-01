Processing steps:<br/>
🎤 The API records the user's voice through the microphone<br/>
🖨️ It processes it to know when the user has finished speaking or is interrupting the assistant<br/>
🤖 It calls an LLM model to generate a response<br/>
📈 It synthesizes the response into speech<br/>
🔊 It plays the synthesized speech through the speakers<br/>
<br/>
Technologies:<br/>
🎤 PyAudio to record the user's voice<br/>
⌨️ Deepgram to transcribe the voice to text<br/>
🤖 OpenAI GPT-3 to generate a response<br/>
📈 ElevenLabs to convert the response to speech<br/>
🔊 Pygame to play the response<br/>
💻 Taipy to display the conversation<br/>
🤝 And a lot of Python code to glue everything together<br/>
<br/>
Shoutout Alexandre Sajus for the projects guide.
