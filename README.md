# The Smallweb Subway
The Smallweb Subway is an experimental project that attempts to bring a
feeling of space to the indie web by using a subway system as a metaphor for
connections between hobby websites!

This is a work in progress, so right now the Smallweb Subway is only made up
of a few small lines (webrings), but I'm slowly adding more interest-based
lines. Once each line reaches a point where it can be visualized nicely,
I'll add it to the [Smallweb Subway Map](https://gusbus.space/smallweb-subway)
to show a visualization of all the lines and how they're connected!

The Smallweb Subway is an open community project and people can request to
join the growing network!

## Instructions to join
If you have a page of your website that is relevant to a line of the
Smallweb Subway and you'd like to have your site added, there are four
things you'll need to do:

1. Identify which line of the Smallweb Subway is most relevant for you to join.
Each line has a specific `KEYWORD` which is important for the
following steps. Right now there are three keywords:
    - `poetry` (Blue Line) : Websites showcasing original poetry.
    - `doodlecrew` (Green Line) : Websites belonging to members of the [Doodle Crew Discord server](https://discord.gg/S3TPjtpPuP).
    - `creativesclub` (Yellow Line) : Websites belonging to member of [Creatives Club](https://creativesclub.art).

2. Get your site info
(URL of page widget will go, title of page, author name/alias)
added to the corresponding JSON file in one of the following ways:
    - Send Gus a DM with your info (@GusBusDraws on most sites), or
    - Email smallwebsubway at gmail dot com, or
    - Submit a pull request on [GitHub](https://github.com/GusBusDraws/smallweb-subway.js)
    editing the corresponding JSON directly.

3. Add the following line to the `<head>` of your page's .html file:
    ```html
    <script src="https://gusbus.space/smallweb-subway.js/KEYWORD.js"></script>
    ```

4. Add the following line to the `<body>` of your page's .html file where
you'd like the widget contained:
    ```html
    <smallweb-subway-KEYWORD></smallweb-subway-KEYWORD>
    ```

If there are no relevant lines for you, you're welcome to suggest a new line
by reaching out to Gus!

## Change Log
### 2024-06-21
- Update the README with instructions to join a line
- Add the poetry line with corresponding files!
### 2024-06-18
- Remove background and border style from widgets
### 2024-06-17
- Rename "smallweb-subway.js" -> [doodlecrew.js](doodlecrew.js) and "data.json" -> [doodlecrew.json](doodlecrew.json)
- Update [smallweb-subway.js](smallweb-subway.js) with "doodlecrew" suffixes for variables
- Add [creativesclub.js](creativesclub.js) and [creativesclub.json](creativesclub.json) with updated variable names to work with [smallweb-subway.js](smallweb-subway.js) on the same page!

### 2024-02-13
- Update DoodleBot address to https://gusbus.space/doodlebot/

### 2023-12-05
- Add Yama to the Doodle Crew ring
- Use concatenated hostname + pathname to find ring data JSON

### 2023-12-01
- Add Meg to the Doodle Crew ring
- Update widget text to exclude Doodle Crew link

### 2023-11-17
- Rename webring data loading functions to have separate names from DoodleBot data loading
- Update the `loadJSON()` function to take a URL as an argument
- Add change log

