# Text Generation in Gemini API

<p>Text generation is a popular form of using ai for the desired works such as writing a blog,
research paper and etc..</p>

### Components in the Text generation 
  
   Gemini can generate text using text,images,video and audio as input

   This is methods are in the models and major methods to access the text generation api.

   - <strong>generateContent</strong>
   - <strong>streamGenerateContent</strong>

### Ways to generate text using the gemini api 

   - Generate text from text-only input
   - Generate text from text-and-image input
   - Generate a text stream
   - Build an interactive chat
   - Enable chat streaming
   - Configure text generation
   - Add system instructions

### API Environment
    
     API_URL=<API_url>  //  url used to fetch
     CONTENT=<CONTENT>  // (generateContent or streamGenerateContent)
     API_KEY=<API_KEY>  // from gemini api_key

### Method 

  `POST` - This is the method used to the all the text generation api calls

  `Content-type` - The type should be application/json for fetching the url.

### Params 
   
Required:        
    `key` - The api_key is the value for the key to autheciate the request.


### Data

   ``` json
   {
      "contents": [
         {
        "parts":
        [{"text": "Write a story about a magic backpack." }]
        }
      ]
   }
   ```

  




     

    

