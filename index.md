# Google Summer of Code with the Mayor's Office of New Urban Mechanics (City of Boston)

Below, you will find a list of ideas we have for a Google Summer of Code contributors for the **summer of 2023**. Thank you for your consideration!

## Guidance for Applications and Project Proposals

You can find guidance for applications and your project proposals **[here](https://monum.github.io/gsoc-2023/guidance)**.

## Ideas List for 2023

### 1. Dashboard for Equity in City Infrastructure

At the Mayor's Office of New Urban Mechanics, we are focused on helping City departments create innovative services that are accessible, equitable, and delightful. We would like to build a tool that helps City departments keep track of infrastructure investments, as they strive to make them more equitable.

Throughout Boston, City government repairs broken sidewalks, installs benches, builds new libraries, and creates new parks. These examples only represent a slice of the enormous investment the City makes in core infrastructure that serves residents. A key question remains: **how equitable are these investments?** For example, are sidewalks repaired at the same rate and the same scale across neighborhoods? Does one neighborhood have more benches per sq.ft or per capita than another neighborhood? Do parks in one neighborhood have more or less amenities than parks on the other side of the city?

We would like to build a web-based dashboard that keeps track of these investments and helps City departments reach their equity goals. The dashboard will use frequently updated open data to help users analyze and visualize trends in infrastructure investments. The dashboard will include a map-based view of several types of infrastructure investments and a variety of charts for users to spot trends over time. 

We give this project a **medium** level of difficulty. The project can be completed in **175 hours**.

This project will require intermediate experience with GIS and web mapping platforms, data visualization frameworks (e.g., D3), data analysis tools (e.g., R), and JavaScript/HTML/CSS.

The mentors for the project will include two Program Directors at the Mayor's Office of Urban Mechanics, including one who served as a Google Summer of Code mentor at Code for America in 2011 and the City of Boston in 2021 and 2022.

### 2. Web Interface for Urban Tree Canopy Detection Using Satellite and Aerial Imagery

The City of Boston's Parks Department maintains a comprehensive data set on trees in Boston. However, it's a manual and laborious process to get the data (such as  conducting site visits for tree counts) on a regular basis. Last summer, a student built a Boston-specific model to identify trees from aerial imagery; it was based on [Deep Forest](https://github.com/weecology/DeepForest), a machine learning library for tree crown detection. 

This year, we would like to operationalize this project for the Parks Department. Right now, the machine learning model runs on Google Colab, which has proven difficult for staff at the Parks Department to learn. They need a simple web interface that allows for the upload of updated imagery and subsequent analysis.

We would also like to explore ways to find more insights from the aerial imagery. For example, we would also like to look at the feasibility of determining tree health and the variety of tree species across the city.

The ideal outcome would be **1)** the creation of a simple web interface for the Parks Department to upload new aerial imagery for analysis, and **2)** the ability to the Parks Department to generate a list of statistics on tree counts and tree healthto ensure that it continues to plants trees in an equitable manner across the city.

We give this project a **medium** level of difficulty. The project can be completed in **175 hours**.

This project will require intermediate experience with Python, machine learning (in particular TensorFlow and training models with imagery), interacting with RESTful APIs, and limited experience with JavaScript, HTML, and CSS.

The mentors for the project will include two Program Directors at the Mayor's Office of Urban Mechanics, including one who served as a Google Summer of Code mentor at Code for America in 2011 and the City of Boston in 2021 and 2022.

### 3. Expanded Translation for the City's 311 App with Machine Learning

In 2010, our office launched the City of Boston's [311 app](https://311.boston.gov/) (one of the first in the nation). The app allows residents to report an array on non-emergency issues (such as potholes) with their smartphones. Historically, the app has only been offered in English, and we have done some of the preliminary work to provide it in other languages. This is a very important issue to address, since up to 33% of the city does not speak English.

[Inspired by the City of San José](https://medium.com/swlh/better-language-translation-through-machine-learning-everything-i-wish-i-knew-6-months-ago-8fa212fb1731), our Google Summer of Code contributor for 2022 created an API-accessible service that improves the translation of text from residents reporting issues through the 311 app. The translation service was based on a custom, trained model using vocabulary frequently associated with City services. Their progress can be found here:

[github.com/monum/311-translation]https://github.com/monum/311-translation

The translation service works well, but still needs improvement for the languages initially tested, namely Spanish and Vietnamese. Moreover, the translation service does not address the following languages used by Boston's residents:

- Simplified Chinese
- Haitian Creole
- Cabo Verdean Creole
- Portuguese
- Russian
- Arabic
- French
- Somali

This summer, we would like to add two more languages to the translation service. The translation service accepts text from a 311 request and return translated text that could be easily understood by our City operations teams. We also benchmark the progress of this translation service against more general translation services.

We give this project a **medium** level of difficulty. The project can be completed in **175 hours**.

This project requires intermediate experience with machine learning, building and training models with text classification, natural language processing, and Python. It will also require intermediate experience with building web service APIs with with a web framework like Flask, Django etc.

The mentors for the project will include two Program Directors at the Mayor's Office of Urban Mechanics, including one who served as a Google Summer of Code mentor at Code for America in 2011 and the City of Boston in 2021 + 2022.

### 4. Data Visualization for the Upcoming At-Home Sensor Network ("Lunchbox of Sensors")

Over the past year, our office has been conducting research and planning on an at-home sensor network called the *Lunchbox of Sensors*. The idea is that city residents could check-out a unified kit of sensors from their local library and use them at home. The internet-connected kits will include sensors for temperature, barometric pressure, relative humidity, temperature, noise, carbon dioxide (a decent measure of ventilation), and a variety of common household air pollutants (VOCs, carbon monoxide, and nitrogen dioxide). We are currently working with a experienced fabrication studio to build a collection of the prototypes.

Since the data from the kits will be available via an API, we would like to build a comprehensive data visualization about the sensor network for the public. At its most basic level, the visualization will display the real-time data collected from the network of sensors on custom maps of the sensor network and animated, interactive charts. Since the sensor data will focus on indoor air environments, the visualization should also incorporate data on the outdoor environment from real-time sources. Finally, the visualization should also provide sociological context, such as providing information on social vulnerability on the maps (via the [CDC's Social Vulnerability Index](https://www.atsdr.cdc.gov/placeandhealth/svi/index.html), for example).

We give this project a **medium** level of difficulty. The project can be completed in **175 hours**.

This project will require intermediate experience with GIS and web mapping platforms, data visualization frameworks like D3, data analysis tools, and JavaScript/HTML/CSS.

The mentors for the project will include two Program Directors at the Mayor's Office of Urban Mechanics, including one who served as a Google Summer of Code mentor at Code for America in 2011 and the City of Boston in 2021 and 2022.
