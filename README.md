Android-Utility
===============
Reference: [Jackson & GSON](http://java.dzone.com/articles/be-lazy-productive-android)  
[JSON Example with Jackson](http://www.mkyong.com/java/jackson-streaming-api-to-read-and-write-json/)

###Jackson Json Processor
1. [Jackson Json Processor](http://jackson.codehaus.org/)
2. Installation in Gradle:  
<code>compile ([group: 'com.fasterxml.jackson.core', name: 'jackson-core', version: '2.4.3'],</code>
<code>[group: 'com.fasterxml.jackson.core', name: 'jackson-annotations', version: '2.4.3'],</code>
<code>[group: 'com.fasterxml.jackson.core', name: 'jackson-databind', version: '2.4.3'])</code>
3. JSON -> Get Specific Value Usage:
4. Object -> JSON Usage:  
<code>ObjectMapper mapper = new ObjectMapper();</code>  
<code>try {  
tempString = mapper.writeValueAsString(mAddress);
        }</code>  
<code>catch (JsonGenerationException e) {
            e.printStackTrace();
        } catch (JsonMappingException e) {
            e.printStackTrace();
        } catch (IOException e) {
            e.printStackTrace();
        }</code>

