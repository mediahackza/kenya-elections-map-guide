# Fundamentals of Data Journalism

## How to make an election map

- Overview Table of contents
  - Election stories you can tell with maps
  - Why should you use a map?
  - Choosing a map type
  - What you will need
- Prepare your data
- Prepare your map file
  - Steps
- Visualise your data with a map
  - Datawrapper
  - Steps
  - Flourish
  - Steps
- Troubleshooting

# Overview

Welcome to _How to make an election map_!

In this guide, we will give you an overview of maps, and some best practice tips as well as
introduce you to two popular data visualisation tools.

We will also take you step-by-step on how to create your own maps with these tools, using the
Kenyan general elections as an example.

Let’s dive right in.

### Election stories you can tell with maps

You can tell several types of data-driven stories pre, during, and post-elections with maps.

We will show you how to make the following two maps:

1. **Pre-elections** : The total number of **registered votersby county** in Kenya.
2. **During and post-elections** (e.g. results announcements):The percentage of **voter**
   **turnout by county** in Kenya.

The data used in this guide is on the 2017 Kenya general elections and was sourced from the
Independent Electoral and Boundaries Commission (IEBC).

```
🌍 While the examples in this guide focus on a specific country’s election, you can
apply what you have learned here to another country too.
```

### Why should you use a map?

Maps can be used for multiple reasons in storytelling.

For instance, they can help you:

```
● answer spatial/ location data questions,
● with analysis and finding patterns ; and
● they can help you to t ell the story of a place.
```

💡 Remember, your map must serve a purpose. If it doesn’t, it’s just decoration.

```
⚠ Is a map the best way to answer your question -and tell a story?
```

```
Ask yourself whether or not you could answer your question faster and easier
with another visualisation like a bar chart.
```

```
Would your audience understand the data - and your story - better if it wasn’t
visualised with a map?
```

### Choosing a map type

There are numerous types of maps and they serve different purposes.

Maps can also be interactive or static. You need to select the type that is most appropriate for
your story.

Here aresome examples:

**Choropleth map**

A choropleth map is a thematic map that uses the intensityof colours and shades to show
values.

```
The Outlier
```

You could create a similar map to the one that you see above by asking certain questions, such
as, “Which African country's population has been vaccinated?”, and “what percentage of the
population has been fully vaccinated?”

A choropleth map is a good visualisation to use to answer those questions.

In this guide, we’re going to create choropleth maps.

**Proportional symbol**

This type of map uses symbols - like circles - to show the proportion of values. Simply put, the
larger the symbol, the more of something there is at that particular location.

```
The Economist
```

In this example from _The Economist_ , the question:“Where is monkeypox spreading fastest” is
answered with a proportional symbol map.

The bigger the circle, the more cases there are in a particular location.

**Locator/ marker**

A locator or marker map gives context to an event.

```
ENCA
```

This type of map shows your audience where something has taken place like the example
above.

A building has collapsed in Nigeria, but where exactly? This locator map shows us where it
happened.

**Heat/ density**

A heat or density map shows clusters of data.

```
The New York Times
```

This animation heatmap example shows how the intensity of fighting in specific locations in
Ukraine appears to be lowering in intensity from March to May 2022.

### What you will need

Before you begin, you will need to have a few things set up.

**Procedure**

There is a process that is followed in data journalism called the data pipeline.

We will cover these steps from the pipeline in the following sections of this document:

1. Prepare your data
2. Prepare your map file
3. Visualise your data with a map

**Tools**

**Google account**
You will need a Google account. If you don’t have an account,sign-up here.

**Mapshaper**
Mapshaperis an editor tool for map data. It converts(and simplifies) large geospatial files into
smaller files e.g. GeoJSON, SHP. And, it’s free.

Map file resources
● The Humanitarian Data Exchange
● openAFRICA
● Regional Centre For Mapping Of Resources For Development(RCMRD)

**Visualisation tools**
Sign-up for free accounts with the below tools. We will demonstrate how to create maps in both
of them in this guide.

1. Datawrapper
   A tool that helps you create visualisations very quickly. It’s free and has subscription
   options.
2. Flourish
   A powerful data storytelling tool. It has more flexible design options than Datawrapper
   and it may take a little longer to put your visualisation together because of all the
   options. It has free and paid subscription options, but special plans are available for
   newsrooms, educators, and non-profits.

# 1. Prepare your data

<insert>

# 2. Prepare your map file

### Steps

```
2.1. Shapefiles
2.1.1. Example:Code for Kenya (2015)
```

2.2. geoJSON
2.2.1. Example:Kenya counties (2015)

# 3. Visualise your data with a map

### Datawrapper

We are going to **create a map** that shows **the totalnumber of registered voters by county** in
Kenya.

The graphic below is the completed map.

### Steps

```
1.1. Create afree Datawrapper accountand log in.
```

```
1.2. In the top right corner of the dashboard, click on the “ Create new... ” button.
Select “ Map ” in the dropdown menu.
```

```
1.3. Click on “ Choropleth map ”.
```

```
1.4. Map creation process
```

**Part 1: Select your map
Part 2: Add your data
Part 3: Visualise
Part 4: Publish and embed**

1.5. **Part 1: Select your map**

```
1.5.1. Click on the “or Upload Map” button. Browse for your geoJSON file.
```

```
1.5.2. When the file has been uploaded, you will receive a preview.
1.5.3. Click on the “Next” button.
```

1.6. **Part 2: Add your data**

```
1.6.1. Open Google Sheets. Copy your data.
```

1.6.2. **Paste the data into the block** provided under the “ **Upload** ” tab.

1.6.3. After pasting your data into the block, **click on the arrow button**.

1.6.4. You will receive a message that confirms that the data has been copied
across into the table.

1.6.5. **Check your data** in the table. Datawrapper will tell you if there is
something amiss.

1.6.6. In this example, Datawrapper says that the county name in this row does
not match with the county name it has on record. This is easy to fix. Click
on the down arrow in the cell and select the county name that matches in
the menu that appears.

1.6.7. Once you’ve made your adjustments, Datawrapper will confirm that all is
in order with a check mark.

1.6.8. You can double-check that the data is correct under the “ **Check** ” tab.

1.6.9. Next, click on the “ **Proceed** ” button.

1.7. **Part 3: Visualise**

```
1.7.1. In this section, you can customise your visualisation further.
```

1.7.2. You will work your way through the customisation process with the
following three tabs, starting with “Refine”.

1.7.3. In order to change the map colours, you may choose one of the colour
palettes provided by Datawrapper or pick your own colours by clicking on
the button with a wrench symbol.

1.7.4. You can display a colour legend in your map. There are a variety of
options that you can apply and enable such as adding an appropriate
caption, formatting, positioning and much more.

1.7.5. Under “Appearance”, you can add a zoom button and also decide where to
position it on the map. Once you’re done, you can click on the blue
“Proceed” button.

1.7.6. Under the “Annotate” tab, you can add a headline, description and credits.

1.7.7. You can also add labels in the “Map labels” section.

1.7.8. Cick on the blue “Proceed” button. You will be taken to the “Layout” tab.

1.7.9. Under the “Layout” tab, you can change the output locale appropriate to
your country. In this example, we have used “English (en-GB)”.

1.7.10. In **“Footer** ” you have several options. For instance, you can make your
data available for download and share an embed link to the public.

1.7.11. Another feature is “Share button” which you can enable for users to share
your map on social platforms. Once you’ve enabled the options you want
under the “Layout” tab, you can click on the blue “Proceed” button.

**1.8. Part 4: Publish & embed**

```
1.8.1. Now that your map is complete, you can publish it. Click on the large blue
“Publish now” button.
```

1.8.2. You will receive a confirmation message stating that your map is
published.

1.8.3. If you want to unpublish it, click on the “unpublish” link below the
“Republish” button.

1.8.4. Datawrapper will generate links and an embed code foryour map too.

1.8.5. You can also download your map and an image.

1.8.6. If you need to make any updates to your map afterward, don’t forget to
“Republish” it for the new changes to appear.

### Flourish

We’re going to **create a map** that shows **voter turnoutby county** in Kenya.

**Comparison**

```
Registered voters by county Voter turnout by county
```

### Steps

```
3.3. Create afree Flourish accountand log in.
```

3.4. Click on the blue “New visualisation” button.
.

3.5. Flourish has an extensive list of the types of visualisations you can create.

3.6. Under “Projection map”, click on “Blank”.

3.7. Lorem ipsum

3.8. Lorem ipsum

3.9. Lorem ipsum

3.10. Lorem ipsum

3.11. Lorem ipsum

3.12. Lorem ipsum

3.13. Lorem ipsum

3.14. Lorem ipsum

3.15. Lorem ipsum

3.16. Lorem ipsum

3.17. Lorem ipsum

3.18. Lorem ipsum

3.19. Lorem ipsum

# 4. Troubleshooting

Sometimes, things don’t go according to plan. Below are some common issues that can happen

- and how to fix them.

```
4.1. Missing data
4.2. geoJSON file opens in a new browser window
```
