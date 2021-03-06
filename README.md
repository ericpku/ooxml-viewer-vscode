# OOXML Viewer VSCode Extension

[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/version/yuenm18.ooxml-viewer.svg)](https://marketplace.visualstudio.com/items?itemName=yuenm18.ooxml-viewer)
[![Build Status](https://dev.azure.com/yuenm18/Extensions/_apis/build/status/yuenm18.ooxml-viewer-vscode?branchName=master)](https://dev.azure.com/yuenm18/Extensions/_build/latest?definitionId=2&branchName=master)

## Features

- [Display the contents of OOXML documents in VS Code](#displays-the-contents-of-ooxml-documents-in-vs-code)
- [Edit the contents of an OOXML documents in VS Code](#edit-the-contents-of-an-ooxml-documents-in-vs-code)
- [Get diff when OOXML documents are edited from outside, e.g. in Microsoft Word, Libre Office Writer, Microsoft Excel, Libre Office Calc, etc.](#user-content-get-diff-when-ooxml-documents-are-edited-from-outside-eg-in-microsoft-word-libre-office-writer-microsoft-excel-libre-office-calc-etc)

### Display the contents of OOXML documents in VS Code

To view the contents of an OOXML document, right click on the file in the context menu, then click on the part you want to view.

![Opening an OOXML Part](https://raw.githubusercontent.com/yuenm18/ooxml-viewer-vscode/master/resources/images/viewing-ooxml-part.gif)

### Edit the contents of an OOXML documents in VS Code

To edit an OOXML part, select the part in the OOXML Viewer menu then edit and save. The changes will be reflected in the OOXML document.

![Editing the contents of an OOXML document in VS Code](https://raw.githubusercontent.com/yuenm18/ooxml-viewer-vscode/master/resources/images/editing-ooxml-part.gif)

### Get diff when OOXML documents are edited from outside, e.g. in Microsoft Word, Libre Office Writer, Microsoft Excel, Libre Office Calc, etc.

When a document opened by the OOXML Viewer is edited from an external program, changed parts are marked with a yellow asterisk, deleted parts are marked with a red asterisk, and new parts are marked with a green asterisk.

To view a diff with the previous version of an OOXML part, right click on the part in the OOXML Viewer menu and click "Compare with Previous".

#### Diff adding text to a docx file

![Getting the diff of an OOXML Part](https://raw.githubusercontent.com/yuenm18/ooxml-viewer-vscode/master/resources/images/getting-diff.gif)

#### Diff adding a slide to a pptx file

![Getting the diff of an OOXML Part](https://raw.githubusercontent.com/yuenm18/ooxml-viewer-vscode/master/resources/images/getting-diff-add.gif)

#### Diff removing a slide from a pptx file

![Getting the diff of an OOXML Part](https://raw.githubusercontent.com/yuenm18/ooxml-viewer-vscode/master/resources/images/getting-diff-delete.gif)


## Release Notes

Please see the [Changelog](CHANGELOG.md)
