
![Page Cover](https://www.notion.so/image/https%3A%252F%252Fwww.notion.so%252Fimages%252Fpage-cover%252Fnasa_buzz_aldrin_on_the_moon.jpg)

# Notion Down

![](https://circleci.com/gh/kaedea/notion-down.svg?style=shield&circle-token=9f4dc656e94d8deccd362e52400c96e709c7e8b3)

[Notion Down](https://github.com/kaedea/notion-down), python tools that convert Notion blog pages into Markdown files, along with intergation to build static webpages such as Hexo.



## Features

What can notion-down do now:

 - Notion pages to basic MarkDown files
 - Notion images downloading
 - Noton custom `ShortCode` blocks that control parametered MD files generating
 - Advanced Notion pageblocks support (WIP)
 - Hexo Integration (WIP)
 - Advanced MarkDown embed feature (WIP)

## Hot It Works

NotionDown read Notion pages data using [notion-py](https://github.com/jamalex/notion-py), and then write pages into MD files.

Basic usage:

> notion-down >> notion-py >> Notion pages data >> generating MD files

Advanced usage:

> WebHook >> notion-down >> notion-py >> Notion pages data >> generating MD files >> Copy into Hexo source >> generating webpages >> push to GitHub pages

## Getting Started

Set `notion_token_v2` at System ENV or `config.py` first, and then check the following procedures.

### UnitTest Examples

See unitest cases at `/test`.

### CI Build Script

See building script at `/.circleci/config.yaml`.

---

> This page is generated by [notion-down](https://github.com/kaedea/notion-down) from [notion.so NotionDown-README](https://www.notion.so/kaedea/NotionDown-README-d3463f3d398743879d663caf87efa029).




<!-- NotionPageWriter
-->