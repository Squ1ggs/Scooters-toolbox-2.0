HOW TO USE THE EDITOR

Basic idea
----------
This editor lets you:
- Build a new item step-by-step
- Import an existing code and edit it
- Convert codes between normal format and BL-Base85 / deserialized
- Mix skins and work with YAML backpack saves

1. Start a new item
-------------------
1. Go to Step 1.
2. Pick the basic info:
   - Item type (gun / grenade / shield / etc.)
   - Manufacturer, weapon type, rarity, etc.
3. Click Next to go to Step 2.

2. Choose main part / barrel (Step 2)
-------------------------------------
1. In Step 2, pick the required main part / barrel from the dropdowns.
2. You can hover tooltips / notes to see what parts do.
3. When you’re happy, click Next.

3. Choose a skin (Step 3)
-------------------------
1. In Step 3, use the Skin dropdown to choose the look you want.
2. This is also the skin list that the Skin Mixer uses.
3. Click Next to move on (you can come back later if needed).

4. Choose an element (optional – Step 4)
----------------------------------------
1. In Step 4, use the Element dropdown.
2. Pick something like Corrosive, Cryo, Fire, Radiation, Shock, or leave it on "No Element (blank)" if you don’t want one.
3. Click Next.

5. Parts & extras (Step 5)
--------------------------
1. In Step 5, choose any extra parts / accessories from the lists.
2. As you change things, the code preview area will update with the current item code.

6. Generate or import codes
---------------------------

Generate from your selections:
- Once Steps 1–5 are filled in, click Generate Code (or equivalent button).
- The editor will show you the item code and/or YAML code in the output panel.

Import an existing code:
1. Paste an existing item code into the Import / Input box.
2. Click Import / Decode.
3. The editor will:
   - Fill in the steps from that code
   - Let you tweak parts, skins, element, etc.
   - Show the decoded structure in the preview area

7. Convert to BL-Base85 / Deserialized
--------------------------------------
Once you have a generated or imported code:
- Click Convert to BL-Base85 to get the BL-Base85 version.
- Click Convert to Deserialized to go the other way.
- The result appears in the output panel; you can copy it out from there.
You should only need to click the conversion buttons once after the fixes.

8. Use the Skin Mixer
---------------------
1. Open the Skin Mixer section.
2. Choose Skin 1, Skin 2 (and optionally Skin 3) from the dropdowns.
   - These lists mirror the normal skin list from Step 3.
3. Click Mix Skins (or the mixer button).
4. The editor will generate a mixed skin code you can apply from the skin list in step 3.

9. YAML Backpack / Save file workflow
-------------------------------------
1. Go to the YAML / Backpack tab/section.
2. Paste in or load:
   - Your existing YAML backpack data, or
   - The YAML for a single item.
3. Use the controls to:
   - Edit / replace items in specific slots
   - Delete or duplicate entries
4. When you’re done, use the Export / Generate .sav button to create an updated save (or YAML) for your game.

10. Saving your work
--------------------
- Copy any codes you need from the output panel.
- Save the HTML file itself locally so you can re-open the toolbox in your browser any time.
- Optional: bookmark the page location on your disk so it’s easy to find.
