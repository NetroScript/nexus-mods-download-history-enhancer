[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]


<br />
<p align="center">

<h3 align="center">Nexus Mods - Improved Download History Filters</h3>

  <p align="center">
    This userscript enhances the Nexus Mods Download History page by adding advanced filtering options. It allows users to filter mods based on their update status and by specific games, making it faster to find mods with updates available.
    <br />
    <br />
    <a href="https://github.com/NetroScript/nexus-mods-download-history-enhancer/issues">Report Bug</a>
    ·
    <a href="https://github.com/NetroScript/nexus-mods-download-history-enhancer/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-userscript">About the UserScript</a>
    </li>
    <li>
      <a href="#installation">Installation</a>
    </li>
    <li>
      <a href="#usage">Usage</a>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## About the UserScript


### Features

- **Filter by Status:** Easily filter mods that have updates available.
- **Filter by Game and Category:** Filter your download history by specific games and their associated categories.
- **Toggle All Options:** Quickly select or deselect all categories for a game or globally using the "Toggle All" buttons.
- **Collapsible Game Sections:** Each game section is collapsible, allowing you to expand or collapse categories for a cleaner view.


### How It Works

#### Filtering by Status

A checkbox allows you to show only outdated downloads. This helps in identifying which mods need updating.

#### Filtering by Game and Category

1. **Game Sections:** Each game in your download history has its own section, which can be expanded or collapsed by clicking the game title. The number of categories available and currently shown are indicated in parentheses.

2. **Category Checkboxes:** Within each game section, categories are listed with checkboxes. You can select or deselect these to filter mods belonging to those specific categories.

3. **Toggle All Buttons:** Each game section has a "Toggle All" button, allowing you to quickly select or deselect all categories within that game. Additionally, there is a global "Toggle All Categories" button at the bottom of the filter container to manage all categories across all games.

#### Applying Filters

The filters are applied automatically as you check or uncheck the checkboxes. The download history table will update to show only the mods that match the selected criteria.


## Installation

As this is a userscript, it requires you to install a userscript manager to make use of this extension.

There are many userscript managers available for all browsers, I myself use Tampermonkey and only tested this with Tampermonkey. Below you have a list with some (you need only one):

* **Violentmonkey** ([Chrome](https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag), [Firefox](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/))
* **Tampermonkey** ([Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo), [Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/))
* **Greasemonkey** ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/))

After installing the userscript manager, you can just click the following link to be prompted to install the userscript:

[nexus-mods-download-history-enhancer.user.js](https://github.com/NetroScript/nexus-mods-download-history-enhancer/raw/master/nexus-mods-download-history-enhancer.user.js)

Alternatively, you could also just install it manually. For that follow the documentation of your userscript manager.

## Usage
After installing the script, navigate to the Nexus Mods Download History page. You will see new filtering options above the table. Select the desired filters to view the mods according to your criteria.

## Contributing

Feel free to add more localisations or improve parts.
To do so:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/NetroScript/nexus-mods-download-history-enhancer.svg?style=for-the-badge
[contributors-url]: https://github.com/NetroScript/nexus-mods-download-history-enhancer/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/NetroScript/nexus-mods-download-history-enhancer.svg?style=for-the-badge
[forks-url]: https://github.com/NetroScript/nexus-mods-download-history-enhancer/network/members
[stars-shield]: https://img.shields.io/github/stars/NetroScript/nexus-mods-download-history-enhancer.svg?style=for-the-badge
[stars-url]: https://github.com/NetroScript/nexus-mods-download-history-enhancer/stargazers
[issues-shield]: https://img.shields.io/github/issues/NetroScript/nexus-mods-download-history-enhancer.svg?style=for-the-badge
[issues-url]: https://github.com/NetroScript/nexus-mods-download-history-enhancer/issues
[license-shield]: https://img.shields.io/github/license/NetroScript/nexus-mods-download-history-enhancer.svg?style=for-the-badge
[license-url]: https://github.com/NetroScript/nexus-mods-download-history-enhancer/blob/master/LICENSE