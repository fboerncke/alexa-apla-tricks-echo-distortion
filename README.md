# Create echo and distortion effects for spoken text using APLA

With devices called "Echo" it should be easy to create **echo** like effects for spoken voice. But surprisingly it turns out that within SSML there is no out of the box support for such a feature. Using some tricks with APLA it is possible though to create various echo and distortion effects for spoken text.

The above example code "**echo-and-distortion.json**" demonstrates one possible approach how to do it. 

## How to do it?

The basic idea is to use APLA to say an utterance **multiple times** in parallel with **increasing small delays**.

## How to configure?

In the example code you can create various echo and distortion effects by modifying the parameters "**offset**" (any integer describing delays in milliseconds) and "**echoNum**" (from 1 to 10) at the very end of the file within the **datasources** segment of the json.

## Use the "Multimodal Responses" feature in the developer console

You can play around, experiment and listen to the effects in the developer console using the "**Multimodal Responses**" option which you can find as an option under the "Build" tab. 

