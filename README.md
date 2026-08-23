# OIWP-POWERFET

>[!CAUTION]
> This branch contains an abandoned revision of POWERFET. It was initially made in late 2023 and was supposed to be released within early to mid of 2024. Unfortunately I got lazy on it and its development weren't smooth and it didn't released. Because of these reasons, POWERFET G2 (which was supposed to be unveiled in late 2024), was made, will be marked official and is recommended for new designs. Please check the known issues section on why the development is not smooth.

This branch contains the first generation of Oitswilliam Pang POWERFET. You may use it for evaluation and not use it for actual hardware uses.

## Known issues
* The P-channel switch uses 100K resistors to turn off, which is known to have unregulated voltage.
    * *In POWERFET G2 however, it instead uses Zener diode to have regulated voltage.* 
* The component identifiers are not standardized.
    * *In later generations or variants of POWERFET, this is fixed.*
