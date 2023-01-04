<header>
<p align="center">
    <img src=".github/images/earthtxt_logo.png" width="20%" height="20%" alt="Earth.txt Logo">
</p>
<h1 align='center' style='border-bottom: none;'>earth.txt</h1>
<h3 align='center'>A .txt file for Earth.</h3>
</header>

<br/>

<div align="center">
  <a href="https://github.com/scape-foundation/earth-txt/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=bug_report.yml">Report a Bug</a>
  |
  <a href="https://github.com/scape-foundation/earth-txt/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Afeature-request%2CHelp+wanted+%F0%9F%AA%A7&template=feature_request.yml">Request a Feature</a>
  |
  <a href="https://github.com/scape-foundation/earth-txt/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Aquestion&template=question.yml">Ask a Question</a>
  |
  <a href="https://github.com/scape-foundation/earth-txt/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Aenhancement&template=suggestion.yml">Make a Sugestion</a>
  |
  <a href="https://github.com/scape-foundation/earth-txt/discussions">Start a Discussion</a>
</div>

<br/>

<div align="center">

[![license](https://img.shields.io/github/license/scape-foundation/earth-txt?color=green&label=license&style=flat-square)](LICENSE.md)
[![website](https://img.shields.io/website?color=blue&down_color=red&down_message=offline&label=website&style=flat-square&up_color=green&up_message=online&url=https%3A%2F%2Fwww.starling.associates)](https://www.earthtxt.org)

![stars](https://img.shields.io/github/stars/scape-foundation/earth-txt?color=blue&label=stars&style=flat-square)
![forks](https://img.shields.io/github/forks/scape-foundation/earth-txt?color=blue&label=forks&style=flat-square)
![downloads](https://img.shields.io/github/downloads/scape-foundation/earth-txt/total?color=blue&label=downloads&style=flat-square)
![sponsors](https://img.shields.io/github/sponsors/scape-foundation?color=blue&label=sponsors&style=flat-square)
![contributors](https://img.shields.io/github/contributors/scape-foundation/earth-txt?color=blue&label=contributors&style=flat-square)

</div>

<br/>
<details open="open">
<summary>Table of Contents</summary>

- [About](#about)
- [Quick Start](#quick-start)
- [Usage](#usage)
- [Website](#website)
- [Authors](#authors)
- [Roadmap](#roadmap)
- [License](#license)
- [Contributing](#contributing)

</details>




> “The Internet is the single biggest thing we’re going to build as a species. This is something if we build it the right way, with the right sources of energy, could really help power our transition to renewables. If we build it the wrong way, it could actually exacerbate the problem.”
>
> — Gary Cook, Greenpeace


## About


**`earth.txt`** is a proposed standard which allows websites to define environmental sustainability policies.


## Quick Start


### 1. Create

#### 1.1 Filename
Create a text file called **`earth.txt`**.
Always use lower-case formatting for the filename.

#### 1.2 Encoding
Make sure that the **`earth.txt`** file is UTF-8 encoded to avoid issues with special characters and multiple languages.


### 2. Place

#### 2.1. well-known Directory
In principle, the **`earth.txt`** file should be placed under the `/.well-known/` path of your website. For example:

```
https://example.com/.well-known/earth.txt
```



#### 2.2. Root Directory
If the `/.well-known/` directory cannot be used for technical reasons, or if you want to use a fallback option, the **`earth.txt`** file can also be placed in the `root` directory of your website. For example:

```
https://example.com/earth.txt
```


The **`earth.txt`** file can be placed in both locations of a website at the same time. Hence, the final directory structure for your website could look like this:

```
example.com/
├── index.html
├── earth.txt
└── .well-known
    └── earth.txt
```


### 3. Link


#### 3.1. Head

Place a reference to the file using a `“help”` tag to the `<head>` section of your website. For example:

```
<link type="text/plain" rel="help" href="https://example.com/earth.txt"/>
```


#### 3.2. Button
Embed a **`earth.txt`** button to your site and link it to your **`earth.txt`** file.


### 4. Serve

#### 4.1. Internet Media Type
The **`earth.txt`** file should have an Internet Media Type of `text/plain`.

#### 4.2. Protocol
The **`earth.txt`** file must be served over HTTPS.


## Template

An example of a valid earth.txt file:

```
# You may contact us at any of the following URLs:
Contact: mailto:example@example.com
Contact: https://example.com/environment
Expires: 2023-01-01T04:59:00.000Z
Acknowledgments: https://example.com/acknowledgments
# Use English or Dutch to conact us please!
Preferred-Languages: en, nl
Canonical: https://example.com/.well-known/earth.txt
Canonical: https://example.com/earth.txt
Policy: https://example.com/environmental_policy
Hiring: https://example.com/careers
```

## Fields


Extensions to earth.txt that will be proposed to the IANA registry.


| **Field Name**         | **Description**                                               | **Multiple Appearances** |
|------------------------|---------------------------------------------------------------|--------------------------|
| Acknowledgments        | link to page where environmental researchers are recognized   | yes                      |
| Canonical              | canonical URI for this file                                   | yes                      |
| Contact                | contact information to use for reporting environmental issues | yes                      |
| Expires                | date and time after which this file is considered stale       | no                       |
| Hiring                 | link to the vendor's environmental-related job positions      | yes                      |
| Policy                 | link to environmental policy page                             | yes                      |
| Preferred-Languages    | list of preferred languages for environmental reports         | no                       |



## Website

- earth.txt Website: [https://www.earthtxt.org](https://www.earthtxt.org "earth.txt website")
- earth.txt GitHub Page: [https://github.com/scape-foundation/earth.txt](https://github.com/scape-foundation/earth.txt "earth.txt GitHub Page")
- Scape Foundation Website: [https://www.scape.foundation](https://www.scape.foundation "Scape Foundation Website")
- Scape Foundation GitHub Page: [https://github.com/scape-foundation](https://github.com/scape-foundation "Scape Foundation GitHub Page")


## Authors

**`earth.txt`** is an open-source project by the [Scape Foundation](https://www.scape.foundation "Scape Foundation website").

The Scape Foundation believes that our cities are the forests of the future. A newfound nature in which ecological, social and economic values are in perfect harmony. The mission of the Scape Foundation is to create regenerative urban landscapes by fusing nature, people and technology into positive future-proof solutions. We set forth to develop co-creation platforms and open-source instruments that bridge the gap between research, design and development.

website: [www.scape.foundation](https://www.scape.foundation "Scape Foundation website")

## Roadmap


## License


Except where otherwise noted, **`earth.txt`** by the Scape Foundation is licensed under the terms of the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/ "Creative Commons Attribution-ShareAlike 4.0 International License"). To view a copy of this license, visit [https://creativecommons.org/licenses/by-sa/4.0/](https://creativecommons.org/licenses/by-sa/4.0/ "Creative Commons Attribution-ShareAlike 4.0 International License") or write to Creative Commons, 171 Second Street, Suite 300, San Francisco, CA 94105, USA.


## Contributing

Contributions from the public are welcome. Refer to the [contribution guidelines](CONTRIBUTING.md) for information on contributing to this project.

