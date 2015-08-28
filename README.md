## Zeppelin COntexte project

### This is the notebook

## How to

1) [Install Zeppelin](https://github.com/apache/incubator-zeppelin) with the latest Spark version. (If it doesn't work with the last one, try with the 1.3).

2) You will need the content of [that pull request](https://github.com/apache/incubator-zeppelin/pull/60) (#60) in order to get the %jdbc  interpreter to work.

Then, the JDBC interpreter should show up in your "Interpreter" tab while running zeppelin ( go in zeppelin and run /bin/zeppelin-daemon.sh start )

## Copy the notes

1) Start zeppelin (./bin/zeppelin-daemon.sh start)
2) Create a new notebook and get its name AND ID
3) Replace the note.json of your newly created notebook by the one from this repo
4) Replace, at the end of the note.js, the name and ID of the notebook. Make it match the new one.
5) Restart Zeppelin.

## Chunks of code

They are organized by order. Simply copy/paste them into a new notbook in zeppelin.

They are separated by "--" After each "--", this is a new note.
