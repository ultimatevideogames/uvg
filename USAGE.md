# Usage and Technical Information

## Adding an item

From the Home screen, select **+**.

There are three ways to add an item:

### Scan

Scan a physical game barcode using the device camera.

The barcode can then be used to search for matching information through the configured eBay integration.

### Search

Search for a game using one or more configured metadata services.

Available integrations include Steam, IGDB, TheGamesDB and eBay.

Returned information can be reviewed and edited before the item is added to the collection.

### Manual

Create an item without using an external service.

Manual entry does not require an API key or an internet connection.

Items can include custom information and images selected through Apple’s photo picker.

---

## Managing the collection

From the Home screen you can:

- Switch between Games, Consoles and Accessories
- Switch between grid and list views
- Search by title
- Filter the collection
- Group or organise items using available fields
- Open an item to view its details

Selecting an item opens its detail screen.

From there, the item can be edited or deleted.

---

## Custom fields

Custom fields can be created in:

**Settings → Global Custom Fields**

A field can apply to Games, Consoles, Accessories or all item types.

Custom fields can be used to record information specific to your collection, such as price paid, serial number or other details.

---

## Steam import

Steam library import is available from:

**Settings → Import Steam Library**

The user must configure their Steam API key and Steam ID.

The app then retrieves the user’s Steam library and can add games that are not already in the collection.

---

## Amiibo import

Amiibos can be imported from:

**Settings → Import Amiibos**

The user can select individual Amiibos or import the available collection.

---

## Custom dataset import

Custom game datasets can be imported from:

**Settings → Import Games Dataset**

The dataset is provided as a ZIP file containing the required JSON data and images.

A sample dataset is available here:

[SNES Test Dataset](https://github.com/ultimatevideogames/uvg/raw/refs/heads/main/DATASET_TEST/SNES_Test.zip)

---

## Backup and restore

Backups are available from:

**Settings → Backup and Restore**

A backup contains the collection data and associated images and is exported as a ZIP file.

The resulting file can be accessed through the Apple Files app.

A previously created backup can be selected and restored through the same screen.

---

## Appearance

Appearance settings are available from:

**Settings → Appearance**

These include:

- Light, dark or system appearance
- Accent colour
- Filled or outline icons
- Haptic feedback

These settings are stored locally.

---

## Delete All Data

The Delete All Data feature is available from:

**Settings → Data → Delete All Data**

The app requires confirmation before the deletion is performed.

This permanently removes the collection data managed by the app from the device.

---

# External Services

The app does not have its own backend server.

When optional integrations are used, requests are made directly from the user’s device to the relevant external service.

The main external services are:

### Apple CloudKit

Used for optional collection synchronisation through iCloud.

### Steam Web API

Used for Steam library import.

### eBay Browse API

Used for barcode and game searches.

### IGDB

Used for game metadata searches.

### TheGamesDB

Used for game metadata searches.

### Amiibo API

Used for Amiibo data and artwork.

Use of these third-party services is subject to their respective terms and privacy policies.
