
<p align="center">
    <img src=".github/images/earthtxt_logo.png" width="20%" height="20%" alt="Earth.txt Logo">
</p>


# earth.txt (WiP)


**A .TXT file for Earth.**

**`earth.txt`** is a proposed standard which allows websites to define environmental sustainability policies.


## Quick Start


### 1. Create

#### 1.1 Filename
Create a text file called **`earth.txt`**. Always use lower-case.

#### 1.2 Encoding
Make the **`earth.txt`** file is UTF-8 encoded to avoid issues with special characters and multiple languages.


### 2. Place

#### 2.1. well-known Directory
In principle, the **`earth.txt`** file should be placed under the `/.well-known/` path of your website. For example:

`https://example.com/.well-known/earth.txt`



#### 2.2. Root Directory
If the `/.well-known/` directory cannot be used for technical reasons, or if you want to use a fallback option, the **`earth.txt`** file can also be placed in the `root` directory of your website. For example:

`https://example.com/earth.txt`


The final directory structure for your website could look like this:

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

`<link type="text/plain" rel="help" href="https://example.com/earth.txt"/>`


#### 3.2. Button
Embed a **`earth.txt`** button to your site and link it to your **`earth.txt`** file.


### 4. Serve

#### 4.1. Internet Media Type
The **`earth.txt`** file should have an Internet Media Type of `text/plain`.

#### 4.2. Protocol
The **`earth.txt`** file must be served over HTTPS.


## Template


```

```

## Website

- earth.txt Website: [https://www.earthtxt.org](https://www.earthtxt.org "earth.txt website")
- earth.txt GitHub Page: [https://github.com/scape-foundation/earth.txt](https://github.com/scape-foundation/earth.txt "earth.txt GitHub Page")
- Scape Foundation Website: [https://www.scape.foundation](https://www.scape.foundation "Scape Foundation Website")
- Scape Foundation GitHub Page: [https://github.com/scape-foundation](https://github.com/scape-foundation "Scape Foundation GitHub Page")


## Authors

**`earth.txt`** is an open-source project by the [Scape Foundation](https://www.scape.foundation "Scape Foundation website").

The Scape Foundation believes that our cities are the forests of the future. A newfound nature in which ecological, social and economic values are in perfect harmony. The mission of the Scape Foundation is to create regenerative urban landscapes by fusing nature, people and technology into positive future-proof solutions. We set forth to develop co-creation platforms and open-source instruments that bridge the gap between research, design and development.

Website: [Scape Foundation](https://www.scape.foundation "Scape Foundation website")

## License

**`earth.txt`** is licensed under the terms of the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/ "Creative Commons Attribution-ShareAlike 4.0 International License").




## Contributing

Contributions from the public are welcome.

### Using the issue tracker 💡

The issue tracker is the preferred channel for bug reports and features requests. [GitHub issues](https://github.com/scape-foundation/earth.txt/issues)

### Issues and labels 🏷

The bug tracker utilizes several labels to help organize and identify issues.

### Guidelines for bug reports 🐛

Use the GitHub issue search — check if the issue has already been reported.
