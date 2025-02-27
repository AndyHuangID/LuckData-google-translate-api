# API Overview

Luckdata google translate api , A simple translate API allows programmatic integration with Google Translate. Same quality result but x100 cheaper. fast and stable. Supported Languages English, Italian, Dutch, German, French, Danish, Chinese (Simplified), Chinese (Traditional), Greek, Japanese, Latin, Belarusian, Czech, Spanish, Laotian, Bulgarian, Thai, Vietnamese, Malay, Burmese, Russian, Portuguese, Mongolian, Farsi, Polish, Filipino, Swedish, Ukrainian, Norwegian, Finnish, Filipino, Icelandic, Hungarian, Javanese, Lithuanian, Hindi, Esperanto, Afrikaans, Hebrew, Maori, Turkish, Malagasy, Irish, Indonesian, Uzbek and 139 other languages.

Luckdata provides an API with 100 free credits every month. This allows small businesses or individuals with low data requirements to use the API for tasks such as testing and data analysis.

# How to Use LuckData-google-translate-api
On the details page, click the pricing plan or subscription button to choose the package that suits you best. You can also select our free trial package. Next, visit the Playground page to test our LuckData-google-translate-api online!

After subscribing successfully, the system will automatically redirect you to the operation page. Choose the appropriate API on the left panel and fill in the required parameters as instructed. Then, test the data you need.

Click the test endpoint, and within moments, receive accurate data. You can choose different data formats to view or directly copy the returned JSON data.

# Simple to Operate, Easy to Learn

You don’t need to use complex code. Use our google-translate-api to meet your business needs. All operations are as simple as copy-paste, even for non-technical users.

## Shell

 <pre> curl -X GET "https://luckdata.io/api/API_Code/?url=Params"  -H 
  "X-Luckdata-Api-Key":" Your API key" </pre>

## python

<pre>
  import requests

  headers = {
      'X-Luckdata-Api-Key': 'Your API key'
  }
  
  json_data={}
  
  response = requests.get(
      'https://luckdata.io/api/google-translate-api/get_09w1',
      headers=headers,
      
  )
  print(response.json())
</pre>
## Java

<pre>
  import java.io.IOException;
import java.net.URI;
import java.net.http.HttpClient;
import java.net.http.HttpRequest;
import java.net.http.HttpResponse;

HttpClient client = HttpClient.newHttpClient();

HttpRequest request = HttpRequest.newBuilder()
    .uri(URI.create("https://luckdata.io/api/google-translate-api/get_09w1"))
    .GET()
    
    .setHeader("X-Luckdata-Api-Key", "Your API key")
    .build();

HttpResponse<String> response = client.send(request, HttpResponse.BodyHandlers.ofString());
</pre>
more about : <a href="https://luckdata.io/marketplace/detail/google-translate-api">LuckData-google-translate-api</a>
