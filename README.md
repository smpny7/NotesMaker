# Notes Maker

This tool converts the JSON file exported by [NoteEditor](https://github.com/setchi/NoteEditor) into CSV data for general sound games.


# Getting Started

1. Write musical score data using NoteEditor.

2. Pass JSON data using redirect or pipe.
```
% python NotesMaker.py < filesFromNoteEditor.json
```

3. The converted CSV file is generated in the current directory.
```
-----------------------------------------------
 Notes Maker (built: June 28 2020) ( MIT )

 github: https://github.com/smpny7/notes-maker
-----------------------------------------------

> Checking for input... ✅
> Checking whether this is a JSON file... ✅
> Converting JSON to CSV file... ✅
> Exporting CSV file... ✅

> Success: Output to the following location.
> /Users/userName/Documents/notes-maker/yourMusicTitle.csv

```


# Related Project
Music score data in [VIVACE](https://github.com/smpny7/vivace) Game is created using Notes Maker.

Official Web Site: <https://smpny7.github.io/vivace-web><br />
Github Repository: <https://github.com/smpny7/vivace>


# Contributing

Please read [CONTRIBUTING.md](https://github.com/smpny7/notes-maker/blob/master/CONTRIBUTION.md) for details on our code of conduct, and the process for submitting pull requests to us.


# License

This project is licensed under the smpny7 - see the [LICENSE.md](https://github.com/smpny7/notes-maker/blob/master/LICENCE) file for details.

*©︎ 2020 smpny7*
