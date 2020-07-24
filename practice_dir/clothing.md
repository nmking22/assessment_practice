## Clothing

**Class: Jacket**

Attributes:
pocket_contents (array)
user (string)
has_hood (boolean)
is_dirty (boolean)
zipper_status (float 0.0 would refer to unzipped and 1.0 would refer to fully zipped)

Methods:
add_item_to_pocket (adds a string to the pocket_contents array)
donate (changes user)
attach hood (changes has_hood value from false to true)
clean (changes is_dirty value from true to false)
zip_up (increases zipper_status by a given amount)
