## A Test Statamic Project

To demonstrate that event listener callbacks can break asset moving / renaming, i.e. AssetReferenceUpdaters

### Credentials
testing@stuartcusack.ie
12345678

### Customisation Notes

1. Installed Statamic
2. Added image field to Pages blueprint
3. Added code to EventServiceProvider

### Steps to Test

1. Add image to page entry
2. Go to assets manager
3. Move image to folder

### Results

- "Undefined array key listener"
- File is in fact moved
- But asset reference updates do not complete.