---
id: CUEwuYsbutHeJJf6aKM3g
title: Basic horizontal with the simplest functionality from each scope
desc: 'VS Code workspace, vaults, intellisense/autocomplete, Dendron settings'
updated: 1655980649961
created: 1632764333519
pods:
  airtable:
    dendron.scopes: rectCR9AOy93xvWQh
    task.scopes: recJj8CAETHiUgcRU
---

Think of this as a horizontal category that picks out the simplest functionality in each scope that is most likely to be used by a customer in their first two weeks. 

VS Code workspace, vaults, intellisense/autocomplete, Dendron settings

## Examples

- validating settings on startup
- opening a file
- autocomplete works for note linking (test vault with at least 100 notes)
- remote vault add

## Features

1. #feature.lookup
2. #feature.hierarchy
3. #feature.markdown
4. #feature.asset-support
5. #feature.links
	-   #feature.wikilinks
	-   #feature.link-to-files
	-   #feature.backlinks
6. #feature.templates
7. #feature.daily-journal
8. #feature.workbench
	- #feature.workbench-vscode
	- #feature.workbench-dendron
9. #feature.easy-start

##  Extension scopes
Since the basics scope only covers what a typical customer would do in two weeks, more functionality related to each vertical can be categorized under the following scopes: 

- Lookup -> #scope.retrieve (#feature.lookup)
- Hierarchies -> #scope.structure (#feature.hierarchy)
- Markdown -> #scope.edit
- Links -> #scope.navigate
- Note references -> #scope.retrieve (#feature.note-refs)
