# 🗲 - Victron Venus Dashboard - 🗲

![Overview](https://github.com/user-attachments/assets/5c450676-acba-4c8b-a558-dc36ff85c208)

<img src="https://github.com/user-attachments/assets/7148bde1-ef7e-4869-b67a-e442fc76ba14" width="300">
<img src="https://github.com/user-attachments/assets/16c48420-e28a-472e-b3df-fe50922d1e70" width="300">

## **What is Victron Venus Dashboard?**

Victron Venus Dashboard is a custom card that replicates the look and feel of the Victron Venus GUI v2 for the [Home Assistant](https://www.home-assistant.io/) Dashboard UI.

---

### ✨ Features

-   🛠  **Full UI Editor**: Configure everything directly in the dashboard editor (no need to edit `yaml`).
-   🔢  **Decimal Precision**: Adjust the number of decimal places for your main sensors directly in the editor.
-   😍  **Icon Picker**: Easily choose icons for your devices.
-   ⚓  **Entity Picker**: Select your Home Assistant entities directly.
-   🚀  **Zero Dependencies**: No need to install additional cards or libraries.
-   🌈  **Material UI**: Designed to fit perfectly with Home Assistant's native design.
-   🌓  **Theme Support**: Supports both light and dark themes (Auto/Manual).
-   🌎  **Multi-language Support**: Fully translated into **English** 🇬🇧, **French** 🇫🇷, **German** 🇩🇪, **Spanish** 🇪🇸, and **Italian** 🇮🇹.

---

## **Installation**

### HACS (Recommended)

This card can be installed via HACS as a custom repository.

1. Open HACS in Home Assistant.
2. Go to **Frontend**.
3. Click the 3 dots in the top right corner and select **Custom repositories**.
4. Add the URL of this repository.
5. Select **Lovelace** as the category.
6. Click **Add**.
7. Search for "Victron Venus Dashboard" and click **Download**.

### Manual Installation

1. Download the `Venus-OS-Dashboard.js` file from the `dist` directory of this repository.
2. Place this file inside your Home Assistant `config/www` directory (e.g., create a folder named `venus-os-dashboard`).
3. Add the resource in **Settings** → **Dashboards** → **Three dots** (top right) → **Resources**.
4. Click on "Add resource" and enter the URL path to the file:
   - Example: `/local/Victron Venus Dashboard/Venus-OS-Dashboard.js`
5. Select "JavaScript Module" and click "Create".
6. Restart Home Assistant (or reload your browser).

And voilà! Victron Venus Dashboard should now be available in the Lovelace card picker menu.

Enjoy! 🎉

---

## Usage

Victron Venus Dashboard can be fully configured using the Dashboard UI editor.

1. In your Dashboard, click the 3 dots in the top right corner.
2. Click _Edit Dashboard_.
3. Click the **Plus (+)** button to add a new card.
4. Search for **Victron Venus Dashboard** in the list.
5. Use the visual editor to:
    - Set up your grid and columns.
    - Add devices (Grid, Battery, Solar, etc.).
    - Select entities for each device.
    - **Set the number of decimals** for your sensor values.
    - Customize icons, names, and styles.

---

## License

This project is licensed under the MIT License.

