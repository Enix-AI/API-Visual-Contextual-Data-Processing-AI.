# API-Visual-Contextual-Data-Processing-AI.
API | Visual/Contextual Data Processing AI.

# Media Analysis
API (Application Programmer's Interface) is the result of our having isolated certain key functional components from the machinery of solutions from Invacio's offerings, and making these components available for your own use. Several are essential utilities such as our media analysis API, which provides access to raw and analyzed media-content, and among other things is able to recognize objects, specify gender, and can even evaluate and track emotional states.

We have also made available APIs able to identify, interpret and extract written language, which can then be subjected to sentiment-analysis; being able to appreciate the tone of phrase, even when the language use is sarcastic or ironic, this is an invaluable capability in a world where a single tweet can so vehemently and drastically affect the markets. Additionally, there are APIs for Landmark Detection, identifying natural and man-made structures within media, and therefore able to locate the picture or video.

Using machine-learning, media API enables users to moderate offensive visual, written content. There is also Optical Character Recognition (OCR), enabling you to detect text within media, and to collect and run sentiment analysis on them as a group batch.

# Perception Media Analysis
Robustly detect broad sets of objects in your medias, from vehicles, architectural structures, and industrial and agricultural objects, to animal and plant life and people...

# Detect Inappropriate Content
Utilising machine-learning to detect content within media that may be inappropriate, offering an easy approach to moderation. Media API enables you to detect different types of inappropriate content from adult to violent content within videos and images.

# Extract and Convert Content to Text
Optical Character Recognition (OCR), enables you to detect text within media, and to collect and run sentiment analysis on them.

----------

# Media Api Features
Derive correlated intelligence from medias with our Innovative Media API

# Label Detection
Detect the topic from your media against broad-sets of categories, ranging from animals and plants to architectural structures and modes of transport.

# Explicit Content Detection
Detect explicit content in real-time to protect your users from adult or violent content.

# Optical Character and Speech Recognition
Detect and extract language from images, videos and voice media.

# Face, Gender and Facial Detection
Detect and count multiple faces within media; determine key facial attributes and decorations; identify and track attitudinal and emotional states; specify gender and even the identity of public and private individuals.

# Media Attributes
Detect generic attributes in media, such as dominant colours [and crop hints].

--------

# Media API Pricing

Media Analysis
For more detailed pricing structure information, please view the pricing structure.

Please Note:Prices show as in Pounds however this service will be operated in current live rate of INV/ENIX apart from Initial INV/ENIX owners assigned against their Email address.

# FEATURE	PRICE / UNIT
OCR or SR Detection	£0.056
Explicit Content Detection	£0.048
Facial, Emotional and Gender Detection	£0.088
* Explicit Content used by itself will be billed at the same prices as Media Properties.

Example: If you apply Facial Detection as well as Label Detection to the samemedia, each feature will be billed individually. You would be billed for 1 unit ofLabel Detection and 1 unit of Facial Detection, at the price dictated by yourmonthly unit volume.

Limits: For more than 5 million units per month,we would ask that you contact us so that we can build custom solutions.Please visit Invacio AAP Holdings Ltd (Seychelles) Contact Page and get in touch.

---------

# Data Analysis
Data Analysis API enables developers to scale and correlate their data points in a simple to use REST API. Our machine learning models and algorithms work from classified points.

# Sentiment Analysis*
Robustly analyse and detect points of interest within private or public data using our natural-language to identify, extract, and determine affective states and meaning.

# Spider Targeted
You simply define specific targets for the Spider after which it quickly locates, collects, sorts, analyses and returns that information to you in clean readable, workable file. Should such capabilities be of interest to your company for any business purpose, we can train models on the fly and assign feeds shaped to your requirements, whatever your area or industry. Please visit our Contact Page to get in touch.

# Spider Non-Targeted and Webbing*
Our spider allows you to define specific targets, after which our system will do the rest, collecting, sorting, analysing and publishing information in clean readable, workable information file. Should such capabilities be of interest to your company for any business purpose, we can train models on the fly and assign feeds shaped to your requirements, whatever your area or industry. Please visit our Contact Page to get in touch.

# Geolocation Constant Aerial Analysis
Custom Solution
Invacio sources tiles from a number of satellite or aerial feeds; we use these extensively within our financial system, observing and processing hundreds of millions of points of interests daily. Should such capabilities be of interest to your company for any business purpose, we can train models on the fly and assign feeds shaped to your requirements, whatever your area or industry. Please visit our Contact Page to get in touch.

# Data API Pricing
Innovative Data Analysis
For more detailed pricing structure information, please view the pricing structure.

Please Note:Prices show as in Pounds however this service will be operated in current live rate of INV/ENIX Rate, apart from initial holders achieve 1 INV/ENIX - 1 Pound in value.

# FEATURE	PRICE / UNIT
Sentiment Analysis & Key Point Extraction	£0.048
Invacio on a number of specific keywords pulling in content for our analyser within Political, Financial, Generic terms, if your specific interest is non-generic please contact us directly

Limits: For more than 5 million units per month,we would ask that you contact us so that we can build customise a solution. Please visit our Contact Page to get in touch.

-----

# Getting Started
Authentication
Getting an API key
To get an API key, please sign up for a API account.
You can find your API key on your account detail page.

Authenticating your requests
You must include your API key with every request you make.
Append your API key to your requests using the api key parameter:
api_key=YOURAPIKEY

# Data Organization
API provide list of content with json reponse.

# Sentiment Analysis & Key Point Extraction
Data API url	https://api.invacio.com/json.php?key=YOURAPIKEY&type=sentiment&content=REQUESTED CONTENT
Format	json

# OCR or SR Detection
Data API url	https://api.invacio.com/json.php?key=YOURAPIKEY&type=ocr&img_url={Replace with Image URL}
Format	json

# Explicit Content Detection
Data API url	https://api.invacio.com/json.php?key=YOURAPIKEY&type=explicit&img_url={Replace with Image URL}
Format	json

# Facial, Emotional and Gender Detection
Data API url	https://api.invacio.com/json.php?key=YOURAPIKEY&type=media_upload&img_url={Replace with Image URL}
Format	json

# Error Codes
We use json response to indicate when errors occur. The following information provides json response for errors returned by the API:

# Without key / type parameter:
Data API url	https://api.invacio.com/json.php
Error	{"status":"error","message":"Missing or Invalid parameter call."}

# Invalid API Key passed:
Data API url	https://api.invacio.com/json.php?key=abcdefghijklmnopqrstuvwxyz
Error	{"status":"error","message":"Invalid api key."}
Invalid parameter TYPE:

# Data API url	
https://api.invacio.com/json.php?key=abcdefghijklmnopqrstuvwxyz&type=test
Error	{"status":"error","message":"Parameter TYPE is not matching with requirement."}
