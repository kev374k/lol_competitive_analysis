# A League of Legends Competitive Analysis

In the ever-evolving landscape of esports, one game stands out as a titan among its peers—League of Legends. As we stride into the heart of 2022, the competitive scene of this multiplayer online battle arena (MOBA) continues to captivate audiences with its strategic depth, intense team dynamics, and the relentless pursuit of victory on the Summoner's Rift.

The year 2022 has witnessed a symphony of skill, innovation, and calculated risk-taking as professional teams from around the world converge to compete in the League of Legends global ecosystem. From the intense battles in regional leagues to the grandeur of international tournaments, each match serves as a canvas where players paint their narratives, leaving an indelible mark on the competitive landscape.

This analysis delves into the multifaceted dimensions of League of Legends esports in 2022. From champion picks and bans to macro and micro plays, we embark on a journey to dissect the strategies, meta shifts, and standout moments that have defined the competitive metagame this year. Join us as we unravel the intricate tapestry of teamwork, adaptation, and individual prowess that shapes the narrative of League of Legends competitive matches in 2022.

As we navigate through the statistics, trends, and standout performances, our aim is to provide a comprehensive exploration of the evolving dynamics within the League of Legends esports sphere. Whether you're a seasoned enthusiast, a casual viewer, or a newcomer to the world of competitive gaming, this analysis serves as a compass, guiding you through the strategic intricacies and compelling stories that make League of Legends a spectacle like no other.

Buckle up as we delve into the heart of the action, unraveling the tales of triumphs, setbacks, and the ever-shifting sands of competitive play in the world of League of Legends in 2022.

## Contents

- [Introduction](#introduction)
- [Cleaning and EDA](#cleaning-and-EDA)
  - [Cleaning](#clening)
  - [EDA (exploratory data analysis)](#exploratory-data-analysis)
  - [Themes](#themes)
  - [Reverse layout](#reverse-layout)
- [Development](#development)
- [Author](#author)
- [License](#license)


## Introduction

In this analysis, we wanted to analyze the best of the best: Competitive Games, and we decided to use a recent year, 2022, to show this. In our analysis, we will analyze one specific question that we believe is very important to how winning games, the primary objective of League, is decided:

<strong>Does a winning top lane affect the probability of a team winning the game?</strong>

This question is especially relevant because we observed (with out eyes) that top lanes often didn't really help a team unless they were doing exceptionally well and could carry the team. Therefore, we wanted to see how often they actually made teams better, and if they did, was it significant to winning in pro-play.


## Cleaning and EDA

Hyde includes some customizable options, typically applied via classes on the `<body>` element.


### Cleaning

<body class = "theme-base-08">
Hyde ships with eight optional themes based on the [base16 color scheme](https://github.com/chriskempson/base16). Apply a theme to change the color scheme (mostly applies to sidebar and links).

![Hyde in red](https://f.cloud.github.com/assets/98681/1831229/42b0b354-7384-11e3-8462-31b8df193fe5.png)

There are eight themes available at this time.

![Hyde theme classes](https://f.cloud.github.com/assets/98681/1817044/e5b0ec06-6f68-11e3-83d7-acd1942797a1.png)

To use a theme, add anyone of the available theme classes to the `<body>` element in the `default.html` layout, like so:

To create your own theme, look to the Themes section of [included CSS file](https://github.com/poole/hyde/blob/master/public/css/hyde.css). Copy any existing theme (they're only a few lines of CSS), rename it, and change the provided colors.
</body>

### Exploratory Data Analysis

![Hyde with reverse layout](https://f.cloud.github.com/assets/98681/1831230/42b0d3ac-7384-11e3-8d54-2065afd03f9e.png)

Hyde's page orientation can be reversed with a single class.

```html
<body class="layout-reverse">
  ...
</body>
```


## Development

Hyde has two branches, but only one is used for active development.

- `master` for development.  **All pull requests should be submitted against `master`.**
- `gh-pages` for our hosted site, which includes our analytics tracking code. **Please avoid using this branch.**


## Author

**Mark Otto**
- <https://github.com/mdo>
- <https://twitter.com/mdo>


## License

Open sourced under the [MIT license](LICENSE.md).

<3
