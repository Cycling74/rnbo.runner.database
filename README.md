# RNBO Runner Content Database

This repository contains user submitted projects for the [RNBO Runner](https://rnbo.cycling74.com/learn/raspberry-pi-target-overview). This includes both projects that are built specifically for [Ableton Move](https://rnbo.cycling74.com/learn/move-intro-and-setup), and those that are for the Raspberry Pi (or another platform that can load the RNBO Runner).

We don't have a friendly web-based interface for browsing and downloading projects. However, you can use this repository to share your work, and to check out what other people have built. If we do eventually build a browsing interface, this repository will be the dataset that we draw from.

## Requirements

- Projects must be Git repositories
- Projects must be open source
- Projects must be formatted as a [Max Package](https://docs.cycling74.com/userguide/packages/)
- Projects must include a LICENSE.md
- Submitted projects should follow our ethical guidelines (see below).

## Project Structure

A project should be a git repository with the same structure as a [Max Package](https://docs.cycling74.com/userguide/packages/). In particular, there should be a `package-info.json` file in the project root, which you can use to describe the project. This includes `name`, a unique identifier for your project, and `displayname`, a human-readable project name.

You can also include an _icon.png_ file, a PNG graphic file (500x500px) for display in any future project browser.

### Exported Graphs

You should put any exported graphs (`.rnbopack` files) into the project's `misc` folder. You can read more about importing and exporting RNBO graphs in the [.rnbopack documentation](https://rnbo.cycling74.com/learn/importing-and-exporting-packages#package-export) here.

### License

Your project repository must have a LICENSE.md file, describing the open-source license under which you are making your code available. Github provides several templates for commonly used licenses, and [describes how to add a license to your repository](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository).

## Adding a Project

Create exactly one thread in the GitHub Issue Tracker per project, with a title equal to your package's `name` (not `displayname`). Post the URL to your repository, and follow the "Updating a Project" section below. This will be your permanent communication channel with the RNBO content database maintainers.

A maintainer will handle your request and post a comment when updated.

### Updating a Project

To inform us of an update to your project, make sure to increment the "version" in your `package-info.json` file (e.g. from 1.2.3 to 1.2.4), and push a commit to your repository. Post a comment in your project's thread (we will re-open it for you) with

- the new version
- the commit hash (given by git log or git rev-parse HEAD). Please do not just give the name of a branch like `master`.

A maintainer will handle your request and post a comment when updated. The issue will be closed when the build is updated.

## Licensing

At this point, we're only accepting project submissions with an open source license, included as a LICENSE.md file in your repository root. You're welcome to use any license of your choosing. Common choices include [MIT](https://opensource.org/licenses/MIT), [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html), [BSD 3-clause](https://opensource.org/license/BSD-3-Clause), and [CC0](https://creativecommons.org/publicdomain/zero/1.0/).

## Ethical Guidelines

In your patches, don't represent as your own any work that you didn't do yourself. You may not clone the brand name, model name, logo, design, or layout of interface elements of an existing hardware or software product without permission from its owner, regardless of whether these are covered under trademark/copyright law.



