# Playnite SteamGridDB Metadata Plugin

A simple addon  for [Playnite](https://playnite.link/) to download metadata from [SteamGridDB](https://www.steamgriddb.com/)!

## Releases

Get the latest release [here](https://github.com/cooperate/SteamGridDBMetadata/releases/latest).

## Usage

In order to use this metadata extension, you first need your SteamGridDB API key. To get this, visit your account on [SteamGridDB](https://www.steamgriddb.com) and click on your profile in the top-right corner. Click `Preferences` and generate an API key if you don't already have one made. Now open Playnite and open `Settings`. Then navigate to the `Metadata Sources` tab. Click `SteamGridDB` and enter your API key in the extension settings box.

To download metadata for a title, right-click it from the Playnite interface and select `Edit...`. Then click `Download Metadata...` in the bottom left-hand corner and select `SteamGridDB` from the list.

## Features

- Downloads backgrounds _(Heroes)_
- Downloads covers _(Grids)_
- Downloads icons
- Custom cover size filter
- Custom cover style filter

## Contributing

- If your project can't find the SDK you need to reference it. Build the solution to generate the SDK under `packages`. The SDK is stored under `.\packages\PlayniteSDK.5.2.0\lib\net462`.