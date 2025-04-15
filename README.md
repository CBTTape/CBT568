# CBT568
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 568 is a load module library which is a set of old TSO    *   FILE 568
//*           computer games.  This library was sent in by Dick     *   FILE 568
//*           Thornton.  The games are circa 1980 or so, and if     *   FILE 568
//*           you include the run-time PL/1-F library from File     *   FILE 568
//*           092 in ISPLLIB or the link list, or get to it some    *   FILE 568
//*           other way, all these games should work fine on        *   FILE 568
//*           current MVS systems.                                  *   FILE 568
//*                                                                 *   FILE 568
//*           emails:  (check to see which are relevant):           *   FILE 568
//*               dickthor@hotmail.com                              *   FILE 568
//*               cthornton@swva.net                                *   FILE 568
//*               rthornton@trigon.com                              *   FILE 568
//*                                                                 *   FILE 568
//*           Please see member $$$NOTES and member GAMERULE in     *   FILE 568
//*           File 569 for further information.  Some of the        *   FILE 568
//*           games have built-in rules instructions.               *   FILE 568
//*                                                                 *   FILE 568
//*      Additional Notes....                                       *   FILE 568
//*                                                                 *   FILE 568
//*      These games were outlawed by management here years ago,    *   FILE 568
//*      but I learned that a co-worker had captured them and       *   FILE 568
//*      renamed them to appear to be production programs based     *   FILE 568
//*      on our corporate naming standards.  I have left the        *   FILE 568
//*      names as-is, but you might want to rename them.  The       *   FILE 568
//*      games are:                                                 *   FILE 568
//*                                                                 *   FILE 568
//*           ZNC1010P is BLACKJACK                                 *   FILE 568
//*           ZNC1020P is TTT (Three-dimensional Tic-Tac-Toe)       *   FILE 568
//*                    (needs PL/1-F library)                       *   FILE 568
//*           ZNC1030P is TARGET                                    *   FILE 568
//*           ZNC1040P is EMPEROR                                   *   FILE 568
//*           ZNC1050P is MASTERMIND (needs PL/1-F library)         *   FILE 568
//*           ZNC1060P is COFFEE                                    *   FILE 568
//*           ZNC1070P is FOOTBALL                                  *   FILE 568
//*           ZNC1080P is STARTREK                                  *   FILE 568
//*           ZNC1110P is a game with numbers in an oval shaped     *   FILE 568
//*                    display (KALAH)                              *   FILE 568
//*                                                                 *   FILE 568
//*      I also found a set of rules that include BLACKJACK,        *   FILE 568
//*      TTT, TARGET, COFFEE, FOOTBALL, and STARTREK.  It is in     *   FILE 568
//*      one of the PDS's I sent earlier, but I will send a copy    *   FILE 568
//*      with this email, as well.  It is member GAMERULE of        *   FILE 568
//*      File 569.                                                  *   FILE 568
//*                                                                 *   FILE 568
//*      To execute the games, I found they work by issuing a       *   FILE 568
//*      CALL for them at the TSO READY prompt.  In ISPF you'd      *   FILE 568
//*      have to go to the command screen or else precede the       *   FILE 568
//*      CALL with "TSO".  Anyway, except for STARTREK, the         *   FILE 568
//*      execute command is:                                        *   FILE 568
//*                                                                 *   FILE 568
//*           "CALL "userid.FILE568.PDS(ZNC1020)"                   *   FILE 568
//*                                                                 *   FILE 568
//*      Which works for all the games except STARTREK              *   FILE 568
//*      (ZNC1080P), which requires that you first allocate two     *   FILE 568
//*      files:                                                     *   FILE 568
//*                                                                 *   FILE 568
//*           "ALLOC F(FT05F001) DA(*)"                             *   FILE 568
//*           "ALLOC F(FT06F001) DA(*)"                             *   FILE 568
//*           "CALL 'userid.FILE568.PDS(ZNC1080P)'"                 *   FILE 568
//*                                                                 *   FILE 568
```
