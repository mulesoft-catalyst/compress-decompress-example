# compress-decompress-example
Example application to showcase Mule 4 Compression Module

**Before you run:**

1) Create ProcessQ in Anypoint MQ
2) Update the properties in Config files such as URL, ClientId and Secret


**How to run:**

Send a json message to the end-point https://localhost:8082/api/enqueue

ex:-
{
  "files/csv.txt": "File,is, great"
}