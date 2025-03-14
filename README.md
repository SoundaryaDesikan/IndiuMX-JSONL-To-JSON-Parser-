Summary 

IndiuMX JSONL To JSON Parser 

API_JSONL_Handler: 

This Java action fetches an API response in JSONL format using the GET method and efficiently transforms it into a structured JSON format. 

Input Parameters required: 

Location: The designated API endpoint for obtaining the response via the GET method. 

Headers: A key-value pair sent as part of an HTTP request or response. 

Header1_Key, Header2_Key: String value of a header key (‘Authorization’, ‘Accept’) 

Header2_Value, Header2_Value: String value of header values  

Pass these input parameters to the Java Action instead of using “Call Rest Activity” in a microflow. The Java action will return a structured JSON response directly based on the provided parameters. 

Convert JSONLtoJSON: 

This Java action transforms a given JSONL input string into a structured JSON format. 

Input Parameters Required: JSONL string value 

Paste your JSONL input into a string variable, pass it as an input parameter for the java action, and get JSON format structure as output. 

JSONL (JSON Lines) is a format for storing structured data, where each line is a separate JSON object. 

JSON (JavaScript Object Notation) represents structured data in an array format, making it easier to process and manipulate in applications. 

Why JSONL? 

JSONL makes it easy to process large datasets because you can read it line by line instead of loading everything at once. 

Some instances where JSONL to JSON conversion required: 

REST API Integrations – Some APIs return JSONL, but Mendix expects JSON. 

Data Processing – JSON is more structured and easier to manipulate. 

Logging & Reporting – Converting logs into JSON arrays for better analysis. 

By implementing these Java Actions, Mendix applications can seamlessly convert JSONL to JSON, improving data handling and integration capabilities. 
