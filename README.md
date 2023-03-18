# Blue marlin

![](screenshot.png)

a _code-first_ component editor for [Makaira](https://makaira.io)

## Features

- [JSON schema validation](https://code.visualstudio.com/docs/languages/json#_json-schemas-and-settings)
- [snippet support](https://code.visualstudio.com/docs/languages/json#_define-snippets-in-json-schemas)
- auto completion

## Usage

The schema will automatically match all files ending with `*.component.json`,
e.g. `banner.component.json` or `discovery-image.component.json`.
Once you're done, copy the whole JSON, open the [components editor](https://docs.makaira.io/docs/components-editor) and import your component there.

## Snippets

Blue marlin comes with several builtin snippets. In order to use them, you need to hit `Ctrl+Space` all the time.
Therefore it is recommended to enable tab-completion and set `"editor.tabCompletion: on"` in your [user or workspace settings](https://code.visualstudio.com/docs/getstarted/settings).
This enables you to [type a snippet prefix](https://code.visualstudio.com/docs/editor/userdefinedsnippets) and press `Tab` to insert a snippet.

### Field snippets

- text
- richtext
- number
- file
- checkbox
- select
- multiselect
- object
- array
- documents
- stream
- colorpicker
- hotspot

### Property snippets

- **uuid**: generates an UUIDv4 (required)
- **id**: kebab-case, lowercase identifier
- label
- type
- description
- option: a single option for _select_ and _multiselect_ fields
- options
- properties
- defaultValue
- documentType

## Release Notes

### 1.0.0

Initial release of Blue marlin.

Happy coding!

## Trivia

> The [Atlantic blue marlin](https://en.wikipedia.org/wiki/Atlantic_blue_marlin) (Makaira nigricans) is a species of marlin endemic to the Atlantic Ocean. It is closely related to, and usually considered conspecific with, the Indo-Pacific blue marlin, then simply called blue marlin. Some authorities still consider both species distinct.
