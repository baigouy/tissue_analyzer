# Tissue Analyzer (JAVA)

This repo contains tutorials for the java version of Tissue Analyzer

## Install

- [Follow the guide](https://github.com/baigouy/tissue_analyzer/blob/main/TA_tutos/install.md)

## Tutos

- [Segment cells](https://github.com/baigouy/tissue_analyzer/blob/main/TA_tutos/tissue_segmentation.md)
- [Edit segmentation](https://github.com/baigouy/tissue_analyzer/blob/main/TA_tutos/correct_segmentation.md)
- [Track cells](https://github.com/baigouy/tissue_analyzer/blob/main/TA_tutos/track_cells.md)

## Toolbars

- [Image](https://github.com/baigouy/tissue_analyzer/blob/main/TA_tutos/image_toolbar.md)
- [List](https://github.com/baigouy/tissue_analyzer/blob/main/TA_tutos/list_toolbar.md)

## Useful shortcuts

- Press the 'i' icon at the bottom of the software to get a thorough list of shortcuts

  - **Left click**: Draw a new contact between two existing ones
  - **Right click**: Remove any pixel from a contact to delete a bond
  - **Enter**: Apply correction (finalize addition or removal of bonds)
  - **Ctrl + S**: Save the current mask (must be done after editing an image)
  - **Shift + Enter**: Apply correction (finalize addition or removal of bonds) and remove small cells (based on an area cutoff)
  - **M**: Show or hide the mask (helps in finding out segmentation errors)
  - **Ctrl + M**: Draw two or more seeds (cell centroids) within an unsegmented region, then press this combination of keys to rerun the watershed segmentation locally, this is much faster than redrawing bonds manually
