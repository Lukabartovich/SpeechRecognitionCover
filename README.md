# SpeechRecognitionCover

This library is using SpeechRecognition and make it easyer to use!!!

This is easy example:


      
      from SpeechRecognitionCover import Cover
      recognizer = Cover()
      while true:
            output = recognizer.recognize()
            print('this is the output' + output)
      
      

If you are in a noisy place:

      
      from SpeechRecognitionCover import Cover
      recognizer = Cover()
      while true:
            output = recognizer.recognize(noises=True)
            print('this is the output' + output)
      
