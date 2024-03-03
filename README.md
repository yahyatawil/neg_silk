# neg_silk.ulp: A Successor to negasilk.ulp

This ULP is an enhancement over the original negasilk.ulp, which processes all polygons (converting them to silkscreen). Therefore, you need to delete the unwanted shapes produced from the other functional polygons. Another enhancement from the old ULP is eliminating the generation of a script file to be executed to finish the ULP’s work. This ULP generates negative silk screen in one step by creating the negative silkscreen, even with the existence of other polygons, by naming the negative one with NEG_SILK.

![gative-silkscreen-eagle-cad-ulp](https://github.com/yahyatawil/neg_silk/assets/1148381/e0404645-4d47-4e84-a584-ba3412476f25)

## Guide
* [neg_silk.ulp](https://atadiat.com/en/e-negative-silkscreen-eagle-ulp/)
* [negasilk.ulp](http://www.electronics-lab.com/create-inverted-silkscreen-cadsoft-eagle/)

# Versions 
| Version              | Eagle Versions  | Contributor      | Note                                                                                         |
|----------------------|-----------------|------------------|----------------------------------------------------------------------------------------------|
| negasilk.ulp         | <= 7.x.x        | Christian Bohrer |                                                                                              |
| neg_silk.ulp         | <= 9.6.x        | Yahya Tawil      |                                                                                              |
| neg_silk_for_fusion  | >= 9.7.x (Fusion)       | Romain Lamothe   | This version drops some features from the neg_silk.ulp until the ULP language (GROUP and DISPLAY) are fixed by the Autodesk team (PRs are welcomed if they are fixed in the future). |

Important Note: This ULP has been tested on Eagle V7.x and Eagle V9.3. However, for some reason, the new Eagle CAD team (following Autodesk's acquisition) made changes to the ULP. Consequently, the ULP may enter a strange loop in some V8.x versions.

