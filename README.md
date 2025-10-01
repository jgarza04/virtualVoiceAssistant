Processing steps:<br/>
🎤 The API records the user's voice through the microphone
🖨️ It processes it to know when the user has finished speaking or is interrupting the assistant
🤖 It calls an LLM model to generate a response
📈 It synthesizes the response into speech
🔊 It plays the synthesized speech through the speakers

Technologies:<br/>
🎤 PyAudio to record the user's voice
⌨️ Deepgram to transcribe the voice to text
🤖 OpenAI GPT-3 to generate a response
📈 ElevenLabs to convert the response to speech
🔊 Pygame to play the response
💻 Taipy to display the conversation
🤝 And a lot of Python code to glue everything together

Shoutout Alexandre Sajus for the projects guide.
