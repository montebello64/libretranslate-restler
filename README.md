# libretranslate-restler

~~~

curl --location --request POST 'http://localhost:8080/translate' \
--header 'Content-Type: application/json' \
--data-raw '{
    "text": "Guten Morgen",
    "targetCode": "cs"
}'

### response

{
    "detectConfidence": 92.0,
    "translatedText": "Dobře ráno",
    "targetCode": "cs",
    "detectLanguage": "de",
    "text": "Guten Morgen"
}

~~~
