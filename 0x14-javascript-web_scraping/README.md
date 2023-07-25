							Working with JSON :
							-------------------

JavaScript Object Notation (JSON) is a standard text-based format for representing structured data based on JavaScript object syntax.
It is commonly used for transmitting data in web applications (e.g., sending some data from the server to the client, so it can be
displayed on a web page, or vice versa). You'll come across it quite often, so in this article, we give you all you need to work with
JSON using JavaScript, including parsing JSON so you can access data within it, and creating JSON.

							    What is JSON?
							    -------------

JSON is a text-based data format following JavaScript object syntax, which was popularized by Douglas Crockford. Even though it closely resembles JavaScript object literal syntax, it can be used independently from JavaScript, and many programming environments feature the ability to read (parse) and generate JSON.

JSON exists as a string — useful when you want to transmit data across a network. It needs to be converted to a native JavaScript objectwhen you want to access the data. This is not a big issue — JavaScript provides a global JSON object that has methods available for
converting between the two.

							   JSON structure:
							   ---------------

As described above, JSON is a string whose format very much resembles JavaScript object literal format. You can include the same basic
data types inside JSON as you can in a standard JavaScript object — strings, numbers, arrays, booleans, and other object literals.
This allows you to construct a data hierarchy, like so:

{
  "squadName": "Super hero squad",
  "homeTown": "Metro City",
  "formed": 2016,
  "secretBase": "Super tower",
  "active": true,
  "members": [
    {
      "name": "Molecule Man",
      "age": 29,
      "secretIdentity": "Dan Jukes",
      "powers": ["Radiation resistance", "Turning tiny", "Radiation blast"]
    },
    {
      "name": "Madame Uppercut",
      "age": 39,
      "secretIdentity": "Jane Wilson",
      "powers": [
        "Million tonne punch",
        "Damage resistance",
        "Superhuman reflexes"
      ]
    },
    {
      "name": "Eternal Flame",
      "age": 1000000,
      "secretIdentity": "Unknown",
      "powers": [
        "Immortality",
        "Heat Immunity",
        "Inferno",
        "Teleportation",
        "Interdimensional travel"
      ]
    }
  ]
}

