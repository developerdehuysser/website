+++
title = "Practical IoT using MicroPython and ESP32"
date = 2017-01-01T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2018-11-05T13:00:00
time_end = 2018-11-05T17:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Abstract and optional shortened version.
abstract = "Measure air quality using MicroPython and ESP32, send it to an MQTT broker and visualize it in Kibana"

# Name of event and optional event URL.
event = "Cegeka workshop"
event_url = "https://example.org"

# Location of event.
location = "Leuven, Belgium"

# Is this a selected talk? (true/false)
selected = true

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["IoT", "MicroPython", "ESP32"]

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = "https://github.com/rdehuyss/IoT-workshop/"

# Does the content use math formatting?
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Right"
+++

The workshop will be about
- using a microcontroller with micropython
- measuring sensor values (temperature, humidity, indoor air quality, ...)
- sending those values to an MQTT Broker
- reading these values automatically from the MQTT broker and indexing them in ElasticSearch
- creating a Kibana dashboard showing these sensor values over time...
- acting based upon those sensor values on another microcontroller
