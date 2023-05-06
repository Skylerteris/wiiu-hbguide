# Installing Aroma

## Preparations

### What do I need?

You will need the latest files from [aroma.foryour.cafe](https://aroma.foryour.cafe/).
    1. Navigate to the **Download** section.
    2. Select `Download Payloads` and `Download Base Aroma`.

### Getting Started

1. Extract and copy the `wiiu` folder from both of the `zip` files you just downloaded and put them on the root of your SD card.
    - If your computer asks you, select yes to merging both of the ``wiiu`` folders.

### Your SD card should look like this:
```
💾sd:
 ┗ 📂wiiu
   ┣ 📂apps
   ┃ ┣ 📜AromaUpdater.wuhb
   ┃ ┣ 📜PayloadLoaderInstaller.wuhb
   ┃ ┗ (All other apps should be here too)
   ┣ 📂environments
   ┃ ┗ 📂aroma
   ┃   ┣ 📂modules
   ┃   ┃ ┣ 📂setup
   ┃   ┃ ┃ ┣ 📜00_mocha.rpx
   ┃   ┃ ┃ ┣ 📜10_wums_loader.rpx
   ┃   ┃ ┃ ┗ 📜99_autoboot.rpx
   ┃   ┃ ┗ (All other Aroma modules ending with .wms should be here too)
   ┃   ┣ 📂plugins
   ┃   ┃ ┣ 📜AromaBasePlugin.wps
   ┃   ┃ ┣ 📜drc_region_free.wps
   ┃   ┃ ┣ 📜homebrew_on_menu.wps
   ┃   ┃ ┣ 📜regionfree.wps
   ┃   ┃ ┗ (All other Aroma plugins ending with .wps should be here too)
   ┃   ┗ 📜root.rpx
   ┣ 📂payloads
   ┃ ┣ 📂default
   ┃ ┃ ┗ 📜payload.elf
   ┃ ┗ 📂nanddumper
   ┃   ┗ 📜payload.elf
   ┣ 📜payload.rpx
   ┗ 📜payload.elf
```

## Finalizing Setup

1. Start the EnvironmentLoader. To do this if you're already autobooting Tiramisu, hold `X` on bootup of your console.
2. Highlight the entry called `Aroma` and press `A` to launch it.
3. You will be brought to a screen called the Boot Selector. Select whatever you want to launch, Wii U menu, Wii Menu whatever.

Congratulations! You are now running Aroma. There is no working version of The Homebrew Launcher for Aroma, so your homebrew will now be in ``.rpx`` and ``.wuhb`` files in `sd:/wiiu/apps/`.