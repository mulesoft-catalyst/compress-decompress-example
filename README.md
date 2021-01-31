# compress-decompress-example
Example application to showcase Mule 4 Compression Module and Base64 <-> Binary conversion.

**Before you run:**

1) Create ProcessQ in Anypoint MQ
2) Update the properties in Config files such as URL, ClientId and Secret


**How to run:**

1) Send a json message to the end-point https://localhost:8082/api/enqueue

It will be compressed and sent to AMQ. Another flow will read the message, decompress and print it in Console.

ex:-
{
  "message": "Mule 4 is great!!"
}

2) Send a .zip file using PostMan as binary file to the end-point https://localhost:8082/api/enqueueFile. The file will be decompressed and printed in console. 
