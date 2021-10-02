# MythicMobs Code Snippets
<p align="center">
    <a href="https://marketplace.visualstudio.com/items?itemName=Monzter.mythicmobs-code-snippets">
        <img alt="Visual Studio Marketplace Version" src="https://img.shields.io/visual-studio-marketplace/v/Monzter.mythicmobs-code-snippets?color=brightgreen">
    </a>
    <a href="https://github.com/Dancull47/mythicmobs-code-snippets-master">
    </a>
    <a href="https://github.com/Dancull47/mythicmobs-code-snippets-master/blob/master/LICENSE">
        <img src="https://img.shields.io/badge/license-GPLv3-blue?style=flat-square" alt="License" />
      </a>
</p>

**[`Extension Page`](https://marketplace.visualstudio.com/items?itemName=Monzter.mythicmobs-code-snippets&ssr=false#overview)**

This extension simplifies the process of creating MythicMobs by providing code snippets for all Mechanics, Conditions, Targeters, and Triggers.  

## Credit

Based on [betonquest-code-snippets](https://github.com/BetonQuest/betonquest-code-snippets)

## Features

* **Tab competition for all Mechanics(Soon), Conditions(Soon), Targeters, and Triggers**

## Quick Guide

![Usage showcase](https://i.imgur.com/FAeNdyE.gif)

You can begin by typing either `-` or a mechanic name for autocompletion to popup.
Upon typing `-` you will see all avaible mechanic and can select any of them.

For this example lets use `damage`! Upon selecting damage, the entire mechanic will be written out, with highlighted areas of the mechanic.
The highlighted areas are ones which you can either fill in or select an option to fill in.

1. The first highlighted area is `number`, directly after the word "amount=" which indicates you should type out a number.
2. Once you type in a number, hit TAB to go to the next highlighted area.
3. Next highlighted is `;ignoreArmor=true`, which is has multiple choices because it's a TRUE or FALSE option. This actually has 3 choices to choose from `;ignoreArmor=true`, `;ignoreArmor=false`, or ` `.
4. You can then use your Arrow Keys to select one of the three option.
5. Upon selecting an option you can then hit TAB to go to the next highlighted area. (NOTE: If you select the ` ` option, then hit BACKSPACE, so a blank space isn't left there! This is an unfortunate limitation of VSCode's snippets.)
6. The final option for this mechanic is `preventknockback=true` which you can once again choose from three options. Upon selecting the option, hit TAB to go to the next highlighted area.
7. The next highlighted area is `@` which indicates your Targetter. You can begin typing out the Targetter OR use CTRL+SPACE which will display every Targetter.
8. Once you select the Targetter, then hit TAB again, which you'll then finally be at the Trigger section `~` and repeat the exact same process as Targetter.

## Release Notes

### 1.0.5

Updated links.

### 1.0.0

Initalized repo with all Triggers & Targeters.