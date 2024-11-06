<variable name="jarFile">
VBook-release-1.4.jar
</variable>

<variable name="example">
To inject this HTML segment in your markbind files, use {{ example }} where you want to place it.
More generally, surround the segment's id with double curly braces.
</variable>

<variable name="commandSummary">

### Command Summary
| Action         | Format                                                                                                                                           | Examples                                                                                                                   |
|----------------|--------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|
| **Add<br>**    | `:add -n NAME -p PHONE_NUMBER -e EMAIL -l LOCATION -t TAG -r REMARK…`<br>`:a -n NAME -p PHONE_NUMBER -e EMAIL -l LOCATION -t TAG -r REMARK…`<br> | `:add -n James Ho -p 98765432 -e jamesho@example.com -l 123, Clementi Rd, 1234665 -t friend -r My favourite colleague`<br> |
| **Clear<br>**  | `:clear`<br>`:cl`<br>                                                                                                                            | `:clear`<br>`:cl`<br>                                                                                                      |
| **Delete<br>** | `:remove -i INDEX`<br>`:rm -i INDEX`<br>                                                                                                         | `:remove -i 3`<br>`:rm -i 3`<br>                                                                                           |
| **Edit<br>**   | `:edit INDEX [-n NAME] [-p PHONE] [-e EMAIL] [-a ADDRESS] [-t TAG]…`<br>`:ed INDEX [-n NAME] [-p PHONE] [-e EMAIL] [-a ADDRESS] [-t TAG]…`<br>   | `:edit 2 -n James Lee -e jameslee@example.com`<br>`:ed 2 -n James Lee -e jameslee@example.com`<br>                         |
| **Quit<br>**   | `:quit`<br>`:q`<br>                                                                                                                              | `:quit`<br>`:q`<br>                                                                                                        |
| **Export<br>** | `:export`<br>`:exp`<br>            123                                                                                                           | `:export`<br>`:exp`<br>                                                                                                    |
| **Find<br>**   | `:find [-n NAME] [-p PHONE] [-e EMAIL] [-a ADDRESS] [-t TAG]…`<br>`:f [-n NAME] [-p PHONE] [-e EMAIL] [-a ADDRESS] [-t TAG]…`<br>                | `:find -n david -l serangoon`<br>`:f -n david -l serangoon`<br>                                                            |
| **Help<br>**   | `:help`<br>`:h`<br>                                                                                                                              | `:help`<br>`:h`<br>                                                                                                        |
| **List<br>**   | `:list`<br>`:ls`<br>                                                                                                                             | `:list`<br>`:ls`<br>                                                                                                       |
| **Redo<br>**   | `:redo`<br>`:r`<br>                                                                                                                              | `:redo`<br>`:r`<br>                                                                                                        |
| **Undo<br>**   | `:undo`<br>`:u`<br>                                                                                                                              | `:undo`<br>`:u`<br>                                                                                                        |


</variable>