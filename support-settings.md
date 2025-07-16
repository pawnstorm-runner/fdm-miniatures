Below you will find support settings for printing miniatures on an FDM 3d printer. These settings assume that you are using [orcaslicer](https://orcaslicer.net).

These settings should be used as a **starting point**. Different models, printers, and filaments may need adjustments.

## Support Settings for Orcaslicer

### Support Section
| **Setting**    | **Value** | **Setting Type** | **Notes** |
| :-------- | :-------: | :---:| :--- |
| Enable support  | yes    | checkbox |   | 
| Type | Tree     | dropdown |   |
| Style    | Organic    | dropdown |   |
| Threshold angle | 25 | dropdown |   |
| Threshold overlap | n/a (greyed out) | dropdown |   |
| First layer expansion | 6mm | number (mm) |   |
| On build plate only | yes | checkbox | turn off to allow supports to start on the model, recommendation is to try changing orientation first |
| Remove small overhangs | yes | checkbox | |

### Raft Section
| **Setting**    | **Value** | **Setting Type** | **Notes** |
| :-------- | :-------: | :---:| :--- |
| Raft layers  | 0    | dropdown | turning on rafts add time and material to prints without much benefit |

## FAQ
* What if I'm not using Orcaslicer?
    * Many slicers for FDM printers are based on the same code, so you will probably be able to find analagous settings in your slicer. However, it is recommended that you use Orcaslicer if you are able to.

