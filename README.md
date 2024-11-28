/Bible available
This command is used to list all available bibles that you can download from the plugin, there are currently 7 different languages.

/Bible downloaded
This command is used to list all of the bibles that the plugin has loaded. Every of this bible can be used in other bibles command. If the bible you need to use is not listed when using this command, you'll either need to load it, or specify it as default loaded bible in the config.yml

/Bible download [name]
This command is used to download a new bible from the plugins available ones, you can simply write the name of the bible (which will need to be one that is listed in the available command).
NOTE: This command requires an internet connection , as it needs to download the raw content of the bible from an external source (GitHub).
This process will usually take a few seconds, a bible file usually weights around 5MBs. You will recieve a message notification when the download has been finished.

/Bible load [name]
This command is used to load a bible that has already been downloaded and has been successfully stored into the /BiblePlugin/bibles/ folder. Loading a bible is a fast process, and you will be notified when the bible has been loaded correctly with a chat message.

/Bible verse [bible] [book:chapter:verse]
This command is used to retrieve a verse from a bible. In the second argument of the command you'll need to specify the name of the bible.
In the third argument you'll need to specify the search for the chapter using the default format , which is BOOKNAME:NUMBER:NUMBER
A few examples can be: [Ezekiel:4:5 , Exodus:6:25]

/Bible verses [bible:book:chapter]
This command is used to know how many verses does a chapter have.
You will need to specify the chapter by using the default format, which is
BIBLENAME:BOOKNAME:NUMBER
You will recieve a message with the total count of verses from that chapter

/Bible chapters [bible:book]
This command is used to know how many chapters does a book from a bible have. You will need to specify the chapter by using the default format, which is BIBLENAME:BOOKNAME
You will recieve a message with the total count of chapters from that book

/Bible books [bible]
This command is used to list every book that a bible has. You will need to specify the name of the bible , and you will recieve a message with the full list of books from that bible.

/Bible occurrences [bible] [word]
This command is a very fast utility to count the total amount of times that a word can be found inside an entire bible. You will need to specify the bible name as second argument, and the word as third argument.
[IMG][URL]https://i.imgur.com/umd6HWy.png[/URL][/IMG]

/Bible occurrences [bible:book] [word]
This command is a very fast utility to count the total amount of times that a word can be found inside a book. You will need to specify the bible name as second argument, and the word as third argument.

/Bible occurrences [bible:book:chapter] [word]
This command is a very fast utility to count the total amount of times that a word can be found inside a chapter. You will need to specify the bible name as second argument, and the word as third argument.

Bible Word for Login Users!
[COLOR=rgb(0, 0, 0)]A random and meaningful verse will be sent to users when joining the server! This feature is useful to encourage your users to reflect about the verse content and start some further reading![/COLOR]
