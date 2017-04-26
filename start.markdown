---
layout: page
title: Getting Started
permalink: /getting-started/
---

# Getting Started

## Downloading Sinap

First, download the appropriate .zip file for your operating system on the releases page:

[https://github.com/2graphic/sinap-ide/releases](https://github.com/2graphic/sinap-ide/releases)

Extract the archive into its own directory.

## Run Sinap

Once extracted, run Sinap.

![initial screen](/assets/tutorial/001_initial_screen.png)

## Loading Plugins

To load a plugin with Sinap, use the plugin manager.

![manage plugins](/assets/tutorial/002_manage_plugins.png)

![plugin manager](/assets/tutorial/003_import_plugins.png)

### Detour

Currently, plugins have to be cloned from GitHub. However, a plugin can be packaged into
a .zip file and loaded into Sinap using the file.

Example:

Clone a plugin from GitHub.
```
$ git clone https://github.com/2graphic/nfa-plugin
```

## Creating a new document

Pretty self explanitory.

![new project](/assets/tutorial/004_new.png)

Select the kind of graph you want to create.

![new project manager](/assets/tutorial/005_new_dialog.png)

## Editing the graph

![blank canvas](/assets/tutorial/006_new_example.png)

Creating nodes can be done by double clicking the canvas. Creating edges can be done
by clicking and dragging from node to node only if the anchor point is visible.

## Interpreting the graph

![blank canvas](/assets/tutorial/007_example_editing.png)

Once you have your graph in place, you can feed it input via the input panel at the bottom
of the screen. There is also support for stepping through and viewing the various steps of
the computation to the right of the input panel.

## Unit testing

Unit testing can be done via the Unit Test panel at the bottom. Click on the Unit Tests icon
to bring it up.