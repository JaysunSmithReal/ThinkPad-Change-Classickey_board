ThinkPads have long been favorites among tech enthusiasts for their outstanding industrial design, exceptional reliability, and extensive expandability—with the classic 7-row keyboard (inherited from IBM, the "Big Blue") being particularly prized.

However, replacing the classic 7-row keyboard with the newer island-style keyboard introduces compatibility issues—such as the Caps Lock indicator failing to light up—and changes certain key mappings. Consequently, flashing a custom EC (Embedded Controller) to remap the keys becomes a necessary step.

Thanks to the contributions of `hamishcoleman` and the `thinkpad-ec` project (https://github.com/hamishcoleman/thinkpad-ec), modifying the ThinkPad EC has become much easier. Yet, since the project is primarily designed to be built within a Linux environment, it can be inconvenient for enthusiasts unfamiliar with Linux or those lacking a Linux setup.

This project provides pre-built images for all supported ThinkPad models—generated on a fresh Debian 11 Linux installation—making it easy for anyone to obtain a ready-to-use ISO image.

Now, you simply need to download the image corresponding to your specific model and use a tool like Rufus or Etcher to write it to a USB drive, allowing you to seamlessly flash your ThinkPad's EC. Before flashing, please consult: https://github.com/hamishcoleman/thinkpad-ec

Happy flashing!