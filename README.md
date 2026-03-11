# Books Sample Library
This is a sample library created to demonstrate what knowledge libraries can look like within the Abstract Folder ecosystem. It serves as a real-world example of how to structure a digital library for the Abstract Folder Obsidian plugin.

## Content Overview
This library includes a curated collection of notes spanning various genres and authors, including:
- **Software**: *Clean Code* by Robert Martin
- **Philosophy**: *Meditations* by Marcus Aurelius
- **Art**: *The Story of Art* by E.H. Gombrich
- **Fiction**: *Palace Walk* by Naguib Mahfouz and *The Blind Owl* by Sadegh Hedayat

It is designed to showcase the "Abstract Folder" plugin's virtual hierarchy. By using the `parent` property in your note's frontmatter, you can organize your knowledge (like these books) without being constrained by the physical file system.



## Setup Instructions
To install this library into your Obsidian vault:

1. Open **Obsidian Settings**.
2. Navigate to **Abstract Folder** > **Library Catalog**.
3. Click **View Catalog** and then navigate to **Manage Catalogs**.
4. Under **Manage Standalone Library**, paste the URL of this repository:
   `https://github.com/RahmaniErfan/Books`
   and click add.
5. This library will now appear in your **Abstract View**.

## For Curators (Engine 2)
Do NOT use `library.json` to trigger updates. When you want to push new notes to your subscribers, you must bump the version and timestamp inside `manifest.json`.


---
*Created with the [Abstract Library Template](https://github.com/RahmaniErfan/abstract-library-template)*
