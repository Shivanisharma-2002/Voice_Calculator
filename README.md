# Voice_Calculator![voiceCalculator](https://user-images.githubusercontent.com/75629990/170265914-fcce600c-2754-4ef5-9674-557cd91d4f7c.png)
FOR SPEECH RECOGNITION
1. For recording, use The SpeechRecognition interface of the Web Speech API.
2. Create a new SpeechRecognition object instance using the SpeechRecognition() constructor
3. Start() of SpeechRecognition will Start the speech recognition service, listening to incoming audio.
4. The onresult event handler will b Fired when the speech recognition service returns a result, as in it fires when the user stoped speaking.
5. Finally, get the transcript of the speech recognition.

Steps to manipulate the voice input

1. Set the voice input to the output section of the calcultor & after 2s the output section will be overridden by the result.
2. Define a function called evaluate for the above funationality.
3. Call the evaluate() after 2s using setInterval method in Javascript.
4. Now, put our eval function under a try catch block. if it works, it will print d result.
   if it doesn't, it comes to catch block where the output is set to empty & the exception is printed into d console
