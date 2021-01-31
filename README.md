# compress-decompress-example
Example application to showcase Mule 4 Compression Module and Base64<->Binary Conversion.

**Before you run:**

1) Create ProcessQ in Anypoint MQ
2) Update the properties in Config files such as URL, ClientId and Secret


**How to run:**

Send a json message to the end-point https://localhost:8082/api/enqueue

ex:-
{
  "message": "Mule 4 Compression is great!!"
}
