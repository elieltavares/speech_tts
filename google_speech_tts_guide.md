# Google Text to Speech API
Base URL: http://translate.google.com/translate_tts  
It converts written words into audio. It accepts `GET` requests.

## GET
`q`  
The query string to convert to audio

`tl`  
Translation language, for example, `ar` for Arabic, or `en-us` for English

`ie`  
Encoding format, use default `UTF-8`


## to download
wget -q -U Mozilla -O output.mp3

Example:
    `wget -q -U Mozilla -O output.mp3 "http://translate.google.com/translate_tts?ie=UTF-8&client=tw-ob&q=$NEXTURL&tl=en"`
    or
    `mpg123 -q "http://translate.google.com/translate_tts?ie=UTF-8&client=tw-ob&q=$NEXTURL&tl=en"`
