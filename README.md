# CSOL Demo Creator

see #proj-csol-demo-creator

This repository contains demo data and a script that can upload the data to Watershed to create a demo measurement / footprint. 


## Setup
Watershed Demo Org
1. Create a Demo org via admin.watershedclimate.com
1. Login to your demo org
1. Create an API key in [the Organization Settings page](https://dashboard.watershedclimate.com/settings/api)


Using the script
1. Follow Step 2 here to create a Github SSH key - [IT Setup](https://www.notion.so/watershedclimate/IT-setup-b87434ae02f64e1bbedf679665839617)
1. Follow Step 1 here to install homebrew - [Local dev setup](https://www.notion.so/watershedclimate/Local-development-environment-setup-2750bbec24854712a4398c8457b4bd87) . If the below steps don't work, maybe try installing the GHG repo and running `./scripts/install-deps` there, which can help ensure you have all the right dependencies (e.g. python)
1. Install vscode
1. Clone this repo via `git clone git@github.com:watershed-climate/csol-demo-creator.git`
1. Run `./scripts/setup` to install dependencies
1. Run `./scripts/run`
1. (optional) install [Graphite](https://graphite.dev/) for easy git version management - `brew install withgraphite/tap/graphite` and then install in vscode via cmd+shift+P > Install Extensions > Graphite > install (it should also be a recommended extension for this repo)

