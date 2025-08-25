# CommanderX16Taipan

A Commander X16 port of the classic Apple II game, Taipan!

The Applesoft BASIC code from the book,  [TAIPAN - A historical adventure for the Apple Computer (PDF)][1] by *Art Canfil*, *Karl Albrecht*, and *Jim McClenahan*, linked to from [taipangame.com][2].

## Notes

### Copy and paste

This code was developed using the emulator [`x16emu`](https://github.com/x16community/x16-emulator), [Release 48 ("Cadmium")](https://github.com/X16Community/x16-emulator/releases/tag/r48), on a macOS (Catalina) host. The code would be pasted into the emulator. 

A (very useful) side effect of pasting the BASIC code into the emulator is that any duplicate lines are ignored, or rather, overwritten. Only the last version of any duplicated lines, in the BASIC source code, is the actual line that is accepted. As a result, there *may* be some duplicated lines left over in the source code. If any duplicated lines are encountered, and you are *manually* entering the code, then save yourself some typing, please use only the last version of that line number.

### Renumbering

Yes, the new X16 port *could* benefit from a **renumber**, so that the lines are not all so "bunched up" together. However, it was felt important to maintain the integrity of the code, and retain the line number ranges used, as they are in the book. Renumbering the code completely would detract from the reading of the book's text, as cross referencing would be so much more difficult.  

## Hacks

 - [Automating the 40 column version of Taipan!](https://github.com/greenonline/TRS80Taipan/edit/main/Misc/Automating/README.md)

## Related repos

 - [!!!NOT!!! TRS80Taipan](https://github.com/greenonline/TRS80Taipan)
 - [MMBASICTaipan](https://github.com/greenonline/MMBASICTaipan)
 - [MacTaipan](https://github.com/greenonline/MacTaipan)
 - [Taipan_40_Column_Apple_II](https://github.com/greenonline/Taipan_40_Column_Apple_II)
 - [BBCTaipan](https://github.com/greenonline/BBCTaipan)

## See also

 - [Taipan! for Commander X16](https://gr33nonline.wordpress.com/2025/08/17/taipan-for-commander-x16/)
 - [Cheats and Hacks - For X16 BASIC, MMBASIC, AppleSoft BASIC and BBC BASIC versions of Taipan](https://gr33nonline.wordpress.com/2025/06/24/automating-40-column-taipan/)


  [1]: https://taipangame.com/pdf/TaipanAHistoricalAdventureForTheAppleComputerAppleIIEdition.pdf
  [2]: https://taipangame.com/
