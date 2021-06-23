<h1>Highlight Text Based On Voice Input - Oracle APEX Dynamic Action Plugin</h1>

Plug-in for highlighting text based on the voice input.<br>
All the langauges supported by google can be used.<br>
<b>Google supported languages:</b> https://support.google.com/googleplay/android-developer/table/4419860?hl=en.
<b>Google supported languages JSON: </b>https://apex.oracle.com/pls/apex/workspace_akil/lang/googlelang/

<h2>Installation</h2>
Import plugin file "dynamic_action_highlight_text_based_on_voice_input.sql" from Source directory into your application.

<h2>How to Use</h2>
  1) Create a Dynamic Action (On Click of a button).<br>
  2) Create a True action.<br>
  3) Select the <b>Highlight Text Based On Voice Input [Plug-in]</b> option.<br>
  4) Plug-in Settings in the Dynamic Action
     <ul>
        <li><b>Language Item:</b> Choose the Page Item that stores the Language Name as Display Value and Language Code as Return Value.</li>
        <li><b>Highlight Color:</b> Choose the Color to highlight the text to be searched.</li>
        <li><b>Voice Input Text Storage Item:</b> Choose the Page Item to store the voice input text.</li>
        <li><b>Button Static ID:</b> Provide the Static ID of the clicked button.(Button that is clicked to start the recording)</li>
     </ul>
  
<h2>Demo</h2>
https://apex.oracle.com/pls/apex/workspace_akil/r/demo/highlight-text-based-on-voice

<h2>Disclaimer</h2>
This plug-in is not supported on all browsers. Please refer the below link for more information.<br>
https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition#browser_compatibility
