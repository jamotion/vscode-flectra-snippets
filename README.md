
<h1 align="center">
  <br>
  <a href="https://marketplace.visualstudio.com/items?itemName=jamotion.flectra-snippets">
  <img src="https://github.com/jamotion/vscode-flectra-snippets/blob/main/images/icon.png?raw=true"></a>
  <br>
  VSCode Flectra Snippets
  <br>
</h1>

<h4 align="center">Develop Flectra modules faster and with no Typing Errors</h4>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=jamotion.flectra-snippets">
    <img src="https://vsmarketplacebadges.dev/version-short/jamotion.flectra-snippets.png?style=for-the-badge&color=875A7B" alt="Version">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=jamotion.flectra-snippets">
<img alt="Visual Studio Marketplace Installs" src="https://img.shields.io/visual-studio-marketplace/i/jamotion.flectra-snippets?color=875A7B&style=for-the-badge">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=jamotion.flectra-snippets">
<img alt="Visual Studio Marketplace Downloads" src="https://img.shields.io/visual-studio-marketplace/d/jamotion.flectra-snippets?color=875A7B&style=for-the-badge">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=jamotion.flectra-snippets">
<img alt="Visual Studio Marketplace Rating" src="https://img.shields.io/visual-studio-marketplace/r/jamotion.flectra-snippets?color=875A7B&style=for-the-badge">
  </a>
</p>


<p align="center">
  <a href="#about">About</a> |
  <a href="#installation">Installation</a> |
  <a href="#usage">Usage</a> |
  <a href="#contributing">Contributing</a> |
  <a href="#release-notes">Release Notes</a> | 
  <a href="#credits">Credits</a>
</p>

## About

This extension contains code snippets for [Flectra](https://www.flectra.com) to help you to develop Flectra modules faster and with no Typing Errors.

All snippets follow the [OCA Maintainer Guidelines](https://github.com/OCA/maintainer-tools/blob/master/CONTRIBUTING.md) and are made to Flectra version `12.0`+.


## Installation

Launch *Quick Open*
  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘P`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

Paste the following command and press `Enter`:

```
ext install jamotion.flectra-snippets
```

## Usage

This extension provide support to following languages (file extensions):

* Python (.py)
* XML (.xml)
* CSV (.csv)

Use `tab` to navegate in snippet positions:

![Peek 2023-03-12 10-37](https://user-images.githubusercontent.com/8174740/224548353-848cce14-18d6-4c67-980d-89414c6e6a0e.gif)

Below is a list of all available snippets.

<details>
<summary>Python snippets</summary>

| Python Snippet | Description                |
| -------------- | -------------------------- |
| `ipdb`         | Import Python ipdb command |


| Flectra Snippet | Description                            |
| ------------ | -------------------------------------- |
| `oman`       | Create Flectra Manifest                   |
| `omod`       | Create New Flectra Model                  |
| `omodi`      | Inherit Existing Flectra Model            |
| `owiz`       | Create New Flectra wizard                 |
| `owizi`      | Inherit Existing Flectra wizard           |
| `omodt`      | Create Test to Flectra Model              |
| `ofbin`      | Add new field Binary                   |
| `ofbool`     | Add new field Boolean                  |
| `ofchar`     | Add new field Char                     |
| `ofdate`     | Add new field Date                     |
| `oftime`     | Add new field DateTime                 |
| `offloat`    | Add new field Float                    |
| `ofhtml`     | Add new field HTML                     |
| `ofint`      | Add new field Integer                  |
| `oftxt`      | Add new field Text                     |
| `ofsel`      | Add new field Selection                |
| `ofm2o`      | Add new field Many2one                 |
| `ofm2m`      | Add new field Many2many                |
| `ofo2m`      | Add new field One2many                 |
| `omcreate`   | Add a method create                    |
| `omwrite`    | Add a method write                     |
| `omunlink`   | Add a method unlink                    |
| `omcomp`     | Add a method compute                   |
| `omchange`   | Add a method onchange                  |
| `ousercomp`  | Add self.user.company_id snippets      |
| `oimp`       | Add Flectra import snippets               |
| `oimpt`      | Add Import to Flectra Tests snippets      |
| `oimper`     | Add Import to Flectra Exceptions snippets |

</details>

<details>
<summary>XML snippets</summary>

| XML Snippet  | Description                              |
| ------------ | ---------------------------------------- |
| `flectra`       | Create Flectra Tag                          |
| `oform`      | Create Form View                         |
| `oformi`     | Inherit Existing Form View               |
| `otree`      | Create Tree View                         |
| `otreei`     | Inherit Existing Tree View               |
| `osearch`    | Create Search View                       |
| `osearchi`   | Inherit Existing Search View             |
| `ograph`     | Create Graph View                        |
| `ographi`    | Inherit Existing Graph View              |
| `opivot`     | Create Pivot View                        |
| `opivoti`    | Inherit Existing Pivot View              |
| `okanban`    | Create Kanban View                       |
| `okanbani`   | Inherit Existing Kanban View             |
| `ocalendar`  | Create Calendar View                     |
| `ocalendari` | Inherit Existing Calendar View           |
| `ogantt`     | Create Gantt View                        |
| `ogantti`    | Inherit Existing Gantt View              |
| `oxpath`     | Add the structure of xpath               |
| `oxpathattr` | Add the structure of xpath to attributes |
| `oact`       | Create new Action                        |
| `onote`      | Add notebook and page tags               |
| `opage`      | Add new page tag                         |
| `omenur`     | Create New Menu Item in the Upper bar    |
| `omenuc`     | Create New Menu Item for Categories      |
| `omenua`     | Create New Menu Item for Actions         |
| `ocron`      | Add a ir.cron record                     |
| `obtn`       | Add Flectra button                          |
| `obtnbox`    | Add Button Box on View                   |
| `ogroup`     | Add group tag on View                    |
| `ofield`     | Add Field on View                        |
| `odata`      | Add data tag on View                     |
| `ochatter`   | Add chatter tag on View                  |
| `oaurl`      | Create action.url tag                    |
| `oaserver`   | Create action.server tag                 |
| `oaclient`   | Create action.client tag                 |

<!-- <summary>QWeb snippets</summary> -->

| Qweb Snippet | Description                                    |
| ------------ | ---------------------------------------------- |
| `oreport`    | Create report record on View                   |
| `otemplate`  | Create template tag                            |
| `otemplatei` | Create template inherit tag                    |
| `otcall    ` | Add t-call tag on View                         |
| `otforeach`  | Add t-foreach tag on View                      |
| `otif`       | Add t-if tag on View                           |
| `otelif`     | Add t-elif tag on View                         |
| `otifelse`   | Add t-if-else tag on View                      |
| `otraw`      | Add t-raw tag on View                          |
| `otesc`      | Add t-esc tag on View                          |
| `otset`      | Add t-set tag on View                          |
| `otfield`    | Add t-field tag on View                        |
| `otimg`      | Add img tag with `t-att-src` attribute on View |

</details>

<details>
<summary>CSV snippets</summary>

| CSVSnippet          | Description                     |
| ------------------- | ------------------------------- |
| `ocolumns`          | Create columns to access groups |
| `flectra_access_entry` | Create entry to access groups   |


</details>

## Contributing

Please, see contributing guidelines [here](CONTRIBUTING.md).

## Release Notes

See [changelog](CHANGELOG.md).

## Credits

This snippets are based in [flectra-pycharm-templates](https://github.com/mohamedmagdy/flectra-pycharm-templates) project.

Copyright (C) 2018-2023 by Michell Stuttgart
